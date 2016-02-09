#### Test 583805004f2b042_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
--------- beginning of system
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1690): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/Search.LoginHelper( 1590): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
I/art     (  823): Explicit concurrent mark sweep GC freed 46667(2MB) AllocSpace objects, 12(192KB) LOS objects, 30% free, 36MB/52MB, paused 2.131ms total 182.461ms
D/SSRM:m  (  823): SIOP:: AP = 380, PST = 442, CUR = 300
V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6584): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6584): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6584): [1] 5.onFinished: Scheduling replication attempt 1.
D/AndroidRuntime( 7206): 
D/AndroidRuntime( 7206): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7206): CheckJNI is OFF
D/AndroidRuntime( 7206): setted country_code = Germany
D/AndroidRuntime( 7206): setted countryiso_code = DE
D/AndroidRuntime( 7206): setted sales_code = DBT
D/AndroidRuntime( 7206): readGMSProperty: start
D/AndroidRuntime( 7206): readGMSProperty: already setted!!
D/AndroidRuntime( 7206): readGMSProperty: end
D/AndroidRuntime( 7206): addProductProperty: start
E/AffinityControl( 7206): AffinityControl: registerfunction enter
D/AndroidRuntime( 7206): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  823): inState():  stateMachine is null !!
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  823): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  823): mDVFSHelper.acquire()
D/FocusedStackFrame(  823): Set to : 0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7228): MountEmulatedStorage()
E/Zygote  ( 7228): v2
I/libpersona( 7228): KNOX_SDCARD checking this for 10200
I/libpersona( 7228): KNOX_SDCARD not a persona
I/ActivityManager(  823): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7228 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7228): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/AndroidRuntime( 7206): Shutting down VM
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 7228): TimaSignature is unavailable
D/ActivityThread( 7228): Added TimaKeyStore provider
V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  823): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  823): Display changed displayId=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetView( 1482): destroyHardwareResources():749311667
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SQLiteSecureOpenHelper( 3574): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3574): getDatabaseLocked(b,b,pwd)...
D/Launcher( 1482): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2282): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/ResourcesManager( 7228): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/WebViewFactory( 7228): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7228): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7228): Loading: webviewchromium
I/LibraryLoader( 7228): Time to load native libraries: 4 ms (timestamps 4556-4560)
I/LibraryLoader( 7228): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7228): Binding Chromium to main looper Looper (main, tid 1) {122fe35e}
I/LibraryLoader( 7228): Expected native library version number "",actual native library version number ""
I/chromium( 7228): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7228): Initializing chromium process, renderers=0
W/art     ( 7228): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7228): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7228): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7228): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7228): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7228): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7228): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7228): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7228): Remote Branch: 
I/Adreno-EGL( 7228): Local Patches: 
I/Adreno-EGL( 7228): Reconstruct Branch: 
W/chromium( 7228): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/ActivityManager(  823): Activity pause timeout for ActivityRecord{2e2ad87 u0 com.test.thalitest/.MainActivity t17}
W/chromium( 7228): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7228): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7228): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7228): CordovaWebView is running on device made by: samsung
W/art     ( 7228): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7228): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7228): performCreate Call secproduct feature valuefalse
D/Activity( 7228): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7228): Render dirty regions requested: true
D/ActivityManager(  823): post active user change for 0
D/KnoxTimeoutHandler(  823): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  823): handleActiveUserChange for user 0
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  823): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  823): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OpenGLRenderer( 7228): Initialized EGL, version 1.4
I/OpenGLRenderer( 7228): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7228): Enabling debug mode 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/InputMethodManagerService(  823): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ActivityManager(  823): mDVFSHelper.release()
I/Timeline(  823): Timeline: Activity_windows_visible id: ActivityRecord{2e2ad87 u0 com.test.thalitest/.MainActivity t17} time:85337
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/IInputConnectionWrapper( 7228): showStatusIcon on inactive InputConnection
,I/Timeline( 7228): Timeline: Activity_idle id: android.os.BinderProxy@2967e609 time:85347
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/chromium( 7228): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7228): 
,E/SMD     (  286): DCD ON
,D/JsMessageQueue( 7228): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7228): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358545024
,I/chromium( 7228): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 7228): Initializing JXcore engine
W/jxcore-log( 7228): JXcore engine is ready
,E/auditd  ( 2095): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  823): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  823): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 7228): Starting JXcore engine
,E/Zygote  ( 7320): MountEmulatedStorage()
,I/ActivityManager(  823): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7320 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 7320): v2
I/libpersona( 7320): KNOX_SDCARD checking this for 1000
I/libpersona( 7320): KNOX_SDCARD not a persona
,I/SELinux ( 7320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7320): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7320): TimaSignature is unavailable
,D/ActivityThread( 7320): Added TimaKeyStore provider
,D/ResourcesManager( 7320): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7228): Platform android
W/jxcore-log( 7228): 
W/jxcore-log( 7228): Process ARCH arm
W/jxcore-log( 7228): 
,D/SecurityLogAgent( 7320):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7320):  SeDenialReceiver : File path = null
,I/ActivityManager(  823): Killing 6251:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,W/libprocessgroup(  823): failed to open /acct/uid_10117/pid_6251/cgroup.procs: No such file or directory
,I/jxcore-log( 7228): JXcore Cordova bridge is ready!
I/jxcore-log( 7228): 
,W/jxcore-log( 7228): JXcore engine is started
,I/jxcore-log( 7228): Toggling radios to true
I/jxcore-log( 7228): 
,D/BluetoothAdapter( 7228): enable()
,D/BluetoothAdapter( 7228): enable(): BT is already enabled..!
,D/WifiService(  823): New client listening to asynchronous messages
,I/WifiManager( 7228): packageName : com.test.thalitest
D/SecContentProvider(  823): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  823): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  823): mCursor = null
,D/WifiService(  823): setWifiEnabled: true pid=7228, uid=10200
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  823): Permission Denial: getCurrentUser() from pid=7228, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  823): Failed getting userId using ActivityManagerNative
W/WifiService(  823): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7228, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  823): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  823): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  823): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  823): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  823): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  823): name = wifi_on
,I/WifiService(  823): disconnect: pid=7228, uid=10200
,I/jxcore-log( 7228): Radios toggled
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): My device name is: samsung-SM-G900F
I/jxcore-log( 7228): 
I/wpa_supplicant( 1280): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1280): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1280): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1280): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1280): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1280): Disconnected - do not scan
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  823): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  823): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  823): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  823): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  823): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  823): do suspend true
,D/WifiP2pService(  823): InactiveState{ what=143375 }
D/WifiP2pService(  823): P2pEnabledState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 1690): Read error: ssl=0xaf41b800: I/O error during system call, Connection timed out
,V/NativeCrypto( 1690): SSL shutdown failed: ssl=0xaf41b800: I/O error during system call, Broken pipe
,E/WifiStateMachine(  823): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  823): updateNetworkInfo()
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): Validated
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  823): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1280): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1280): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1280): First Scan Start
E/WifiStateMachine(  823): ConnectModeState: Network connection lost 
I/wpa_supplicant( 1280): Scan requested (ret=0) - scan timeout 30 seconds
I/WifiTrafficPoller(  823): evaluateTrafficStatsPolling
,E/WifiStateMachine(  823): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  823): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/CLocInfoService(  823): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  823): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  823): do suspend true
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/WifiP2pService(  823): InactiveState{ what=143375 }
,D/WifiP2pService(  823): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1298): Starting #6
,I/Hs20UtilService( 1298): Message received 5007
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService(  823): calling update connectivity
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  823): Not allowed due to - mEnabled false
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  823): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  823): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): Disconnected - quitting
,E/WifiStateMachine(  823): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/WifiTrafficPoller(  823): evaluateTrafficStatsPolling
,D/WifiStateMachine(  823): updateConfiguredNetworkExpiration - currTime: 1455035769946
D/WifiStateMachine(  823): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
I/CLocInfoService(  823): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  823): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  823): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  823): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  823): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  823): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  823): setDetailed state send new extra info"NG700"
,D/TelephonyNetworkFactory( 1476): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  823): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SecContentProvider2(  823): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  823): mCursor = null
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  823): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  823): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  823): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
,V/NetworkStats(  823): updateIfacesLocked()
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
V/NetworkStats(  823): performPollLocked(flags=0x1)
E/ConnectivityService(  823): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  823): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkStatsFactory(  823): UpdateStatsForKnox
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  823): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  823): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  823): currentTimeMillis() cache hit
,D/NtpTrustedTime(  823): currentTimeMillis() cache hit
V/NetworkStats(  823): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
,V/NetworkStats(  823): performPollLocked() took 7ms
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/SecContentProvider2(  823): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  823): mCursor = null
,I/Hs20UtilService( 1298): Starting #7
,I/Hs20UtilService( 1298): Message received 5007
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime(  823): currentTimeMillis() cache hit
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1476): FileWriteThread : threadType = 3
,I/PowerManagerService(  823): [PWL] Off : 15s ago
,I/PowerManagerService(  823): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  823): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  823): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2474, ws=null) (elapsedTime=51777)
I/PowerManagerService(  823): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=823, ws=null) (elapsedTime=108)
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  823): updateDataUsageMap
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/SmartBondingService(  823): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  823): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
,D/SmartBondingService(  823): getSBEnabled() enabled =false
,D/SmartBondingService(  823): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  823): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  823): CLoinfo wifi false
,W/SLocation(  823): No Active Data Connection
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2282): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6711): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6711): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6711): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6711): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6711): noConnectivity : true
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3821): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7373): MountEmulatedStorage()
I/libpersona( 7373): KNOX_SDCARD checking this for 10126
E/Zygote  ( 7373): v2
I/libpersona( 7373): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7373 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/DBG_DM  ( 3821): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SELinux ( 7373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7373): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7373): TimaSignature is unavailable
,D/ActivityThread( 7373): Added TimaKeyStore provider
,D/ResourcesManager( 7373): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore( 7373): Database version: 104
,D/ResourcesManager( 7373): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7373): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7373): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7373): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7373): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7373): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16af99b8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7373): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7373): GMSCore installation verified
,I/ConfigStore( 7373): Config Database version: 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7373): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7373): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7373): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1280): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 1280): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1280): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1280): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  823): [1,455,035,770,968 ms] noteScanEnd no scan source
,E/WifiStateMachine(  823): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@4e6306e sup_state=SCANNING debouncing=false
,I/CLocInfoService(  823): External Intent Received android.net.wifi.SCAN_RESULTS
E/WifiStateMachine(  823): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  823): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  823): setDetailed state send new extra info0x
D/SecContentProvider2(  823): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  823): mCursor = null
,D/WifiDisplayAdapter(  823): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  823): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/AudioPolicyManager(  292): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  823): getStreamVolume 3 index 70
,I/MediaRouter( 7373): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7412): MountEmulatedStorage()
E/Zygote  ( 7412): v2
I/libpersona( 7412): KNOX_SDCARD checking this for 10002
I/libpersona( 7412): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7412 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1280): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  823): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  823): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/wpa_supplicant( 1280): Associated with C0.AA.48
,D/SecContentProvider2(  823): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  823): mCursor = null
,I/wpa_supplicant( 1280): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  823): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  823): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  823): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  823): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  823): mCursor = null
,I/wpa_supplicant( 1280): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/SELinux ( 7412): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7412): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7412): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1280): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  823): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  823): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1280): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1280): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1280): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1280): Blacklist: Clear (temp) 
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  823): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  823): mCursor = null
,E/WifiStateMachine(  823): Network connection established
,D/WifiNative-HAL(  823): callSECApiVoid - ID [50]
,E/WifiStateMachine(  823): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  823): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  823): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  823): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  823): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  823): Got NetworkAgent Messenger
D/ConnectivityService(  823): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  823): updateNetworkInfo()
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  823): NetworkAgent connected
,V/AlarmManager(  823): waitForAlarm result :4
,D/WifiDisplayAdapter(  823): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/WifiStateMachine(  823): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  823): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  823): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 7412): TimaSignature is unavailable
,D/ActivityThread( 7412): Added TimaKeyStore provider
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 2
I/NetworkMonitor( 7373): type=WIFI subType= reason=null isConnected=false
,E/WifiStateMachine(  823): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  823): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  823): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/ActivityManager(  823): Killing 6473:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/ResourcesManager( 7412): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4263, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  823): stay LED for fully charged
D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  823): Plugged
I/MotionRecognitionService(  823): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,W/libprocessgroup(  823): failed to open /acct/uid_10075/pid_6473/cgroup.procs: No such file or directory
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager(  823): Killing 6495:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7439): MountEmulatedStorage()
I/libpersona( 7439): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7439): v2
I/libpersona( 7439): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/WifiStateMachine(  823): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  823): do suspend false
,D/SecContentProvider2(  823): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  823): mCursor = null
,D/WifiP2pService(  823): InactiveState{ what=143375 }
D/WifiP2pService(  823): P2pEnabledState{ what=143375 }
,I/SELinux ( 7439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7439): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  823): failed to open /acct/uid_1000/pid_6495/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7439): TimaSignature is unavailable
,D/ActivityThread( 7439): Added TimaKeyStore provider
,D/ResourcesManager( 7439): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7439): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7439): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7439): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7439): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7439): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7439): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/dhcpcd  ( 7457): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7457): version 5.5.6 starting
,E/dhcpcd  ( 7457): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7457): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7457): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 7457): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7457): bssid match
,I/dhcpcd  ( 7457): wlan0: rebinding lease of 192.168.1.135
,E/Zygote  ( 7465): MountEmulatedStorage()
,E/Zygote  ( 7465): v2
I/libpersona( 7465): KNOX_SDCARD checking this for 10011
I/libpersona( 7465): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7465 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7465): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7465): TimaSignature is unavailable
,D/ActivityThread( 7465): Added TimaKeyStore provider
,D/ResourcesManager( 7465): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  823): Killing 6539:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7465): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7465): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7465): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7465): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7465): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7480): MountEmulatedStorage()
E/Zygote  ( 7480): v2
I/libpersona( 7480): KNOX_SDCARD checking this for 10019
I/libpersona( 7480): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7480 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  823): Killing 6673:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/art     (  313): Explicit concurrent mark sweep GC freed 8714(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 269us total 11.717ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.496ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.997ms
,I/SELinux ( 7480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027,
E/SELinux ( 7480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7480): TimaSignature is unavailable
,D/ActivityThread( 7480): Added TimaKeyStore provider
,D/ResourcesManager( 7480): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7480): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7480): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1455035771752
,I/KLMS-2.4.503: ( 7480): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7480): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7480): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  823): Killing 6692:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7500): MountEmulatedStorage()
,E/Zygote  ( 7500): v2
I/libpersona( 7500): KNOX_SDCARD checking this for 10037
I/libpersona( 7500): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7500 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  823): failed to open /acct/uid_1000/pid_6539/cgroup.procs: No such file or directory
,W/libprocessgroup(  823): failed to open /acct/uid_10015/pid_6673/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7500): TimaSignature is unavailable
,D/ActivityThread( 7500): Added TimaKeyStore provider
,D/ResourcesManager( 7500): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7500): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5131): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,W/libprocessgroup(  823): failed to open /acct/uid_10016/pid_6692/cgroup.procs: No such file or directory
,I/SA      ( 6749): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6749): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6749): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6749): [SLFUCHKMGR] constructor called
,I/SA      ( 6749): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6749): [OR] == isSIMCardReady false ==
,I/SA      ( 6749): [SCU] == networkStateCheck == false
I/SA      ( 6749): [OR] onReceive END
,E/SPPClientService( 5131): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7517): MountEmulatedStorage()
,E/Zygote  ( 7517): v2
I/libpersona( 7517): KNOX_SDCARD checking this for 10071
I/libpersona( 7517): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7517 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  823): Killing 6447:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7517): TimaSignature is unavailable
,D/ActivityThread( 7517): Added TimaKeyStore provider
,D/ResourcesManager( 7517): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7517): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7517): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7517): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7517): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7517): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7517): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7517): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7517): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7517): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7517): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7517): [KK AccuPhone]>>> ==============================================================================================
D/SettingsProvider(  823): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  823): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  823): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  823): selectionArgs: false
D/SettingsProvider(  823): selectionArgs: 10071
D/SecContentProvider(  823): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  823): ret = -1
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7517): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7517): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7517): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7517): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7517): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7517): [KK AccuPhone]>>> RM:136 [0:0]  V init 
W/libprocessgroup(  823): failed to open /acct/uid_10034/pid_6447/cgroup.procs: No such file or directory
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7517): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7517): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7517): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7517): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7534): MountEmulatedStorage()
E/Zygote  ( 7534): v2
I/libpersona( 7534): KNOX_SDCARD checking this for 1000
I/libpersona( 7534): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7534 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  823): Killing 4705:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7534): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7534): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7534): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7534): TimaSignature is unavailable
,D/ActivityThread( 7534): Added TimaKeyStore provider
,W/libprocessgroup(  823): failed to open /acct/uid_10035/pid_4705/cgroup.procs: No such file or directory
,D/ResourcesManager( 7534): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7534): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7534): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7534): premStatus:2
,I/KnoxUsageLogPro( 7534): isEulaShown : false
I/KnoxUsageLogPro( 7534): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7549): MountEmulatedStorage()
E/Zygote  ( 7549): v2
I/libpersona( 7549): KNOX_SDCARD checking this for 10088
I/libpersona( 7549): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7549 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  823): Killing 6025:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7549): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7549): TimaSignature is unavailable
,D/ActivityThread( 7549): Added TimaKeyStore provider
,D/ResourcesManager( 7549): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  823): failed to open /acct/uid_10042/pid_6025/cgroup.procs: No such file or directory
,I/ActivityManager(  823): Killing 5970:com.sec.android.gallery3d/u0a48 (adj 15): bgCount ##41
,D/Headlines( 5484): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5484): getCountryCode(): countryCode = DE
,D/Headlines( 5484): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5484): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5484): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5484): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5484): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5484): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5484): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7568): MountEmulatedStorage()
E/Zygote  ( 7568): v2
I/libpersona( 7568): KNOX_SDCARD checking this for 10128
I/libpersona( 7568): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7568 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7568): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7568): TimaSignature is unavailable
,D/ActivityThread( 7568): Added TimaKeyStore provider
,W/libprocessgroup(  823): failed to open /acct/uid_10048/pid_5970/cgroup.procs: No such file or directory
,D/ResourcesManager( 7568): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7568): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7568): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7568): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7568): Loading: webviewchromium
,I/LibraryLoader( 7568): Time to load native libraries: 4 ms (timestamps 969-973)
,I/LibraryLoader( 7568): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7568): Binding Chromium to main looper Looper (main, tid 1) {6817ccc}
,I/LibraryLoader( 7568): Expected native library version number "",actual native library version number ""
,I/chromium( 7568): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7568): Initializing chromium process, renderers=0
,W/art     ( 7568): Attempt to remove local handle scope entry from IRT, ignoring
,V/AlarmManager(  823): waitForAlarm result :4
,W/chromium( 7568): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7568): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7568): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid( 7568): Requires BLUETOOTH permission
,I/Adreno-EGL( 7568): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7568): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7568): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7568): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7568): Remote Branch: 
I/Adreno-EGL( 7568): Local Patches: 
I/Adreno-EGL( 7568): Reconstruct Branch: 
,I/dhcpcd  ( 7457): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/NSApplication( 7568): Starting up...
,I/dhcpcd  ( 7457): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  823): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  823): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  823): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  823): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7630 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 7630): MountEmulatedStorage()
I/ActivityManager(  823): Killing 5636:com.android.mms/u0a50 (adj 15): bgCount ##41
E/Zygote  ( 7630): v2
I/libpersona( 7630): KNOX_SDCARD checking this for 10138
I/libpersona( 7630): KNOX_SDCARD not a persona
,I/SELinux ( 7630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/CountryDetector(  823): No listener is left
,I/SELinux ( 7630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7630): TimaSignature is unavailable
,D/ActivityThread( 7630): Added TimaKeyStore provider
,W/libprocessgroup(  823): failed to open /acct/uid_10050/pid_5636/cgroup.procs: No such file or directory
,D/ResourcesManager( 7630): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7630): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7630): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7630): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7630): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7630): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7630): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7666): MountEmulatedStorage()
E/Zygote  ( 7666): v2
I/libpersona( 7666): KNOX_SDCARD checking this for 10163
I/libpersona( 7666): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7666 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  823): Killing 6770:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,E/WifiStateMachine(  823): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  823): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  823): do suspend true
,I/SELinux ( 7666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiP2pService(  823): InactiveState{ what=143375 }
D/WifiP2pService(  823): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  823): WifiStateMachine DHCP successful
,E/WifiStateMachine(  823): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  823): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  823): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  823): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  823): Not connected state, yet.
E/WifiStateMachine(  823): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  823): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  823): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  823): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  823): callSECApiInt - ID [210]
,E/WifiStateMachine(  823): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  823): updateNetworkInfo()
,D/ConnectivityService(  823): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  823): Adding iface wlan0 to network 503
,D/TimaKeyStoreProvider( 7666): TimaSignature is unavailable
D/ActivityThread( 7666): Added TimaKeyStore provider
,I/CLocInfoService(  823): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  823): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  823): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  823): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  823): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  823): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7666): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7666): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup(  823): failed to open /acct/uid_10051/pid_6770/cgroup.procs: No such file or directory
,W/ResourcesManager( 7666): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  823): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  823): Now, connected state.
E/WifiStateMachine(  823): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  823): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  823): evaluateTrafficStatsPolling
,D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,I/CLocInfoService(  823): External Intent Received android.net.wifi.STATE_CHANGE
E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  823): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  823): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  280): QcRouteController
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  823): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  823): mBoosterFLAG : 0
I/WifiTrafficPoller(  823): current booster mode : FullMode
D/WifiNative-HAL(  823): callSECApiVoid - ID [212]
E/WifiStateMachine(  823): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/CLocInfoService(  823): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,V/        (  280): QcRouteController
,I/WifiStateMachine(  823): REQUEST_POWER_SAVE_ON
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,D/RCPManagerService(  823): exchangeData() failure , invalid userId
,V/        (  280): QcRouteController
,D/RCPManagerService(  823): exchangeData() failure , invalid userId
,D/ConnectivityService(  823): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  823): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  823): updateNetworkInfo()
D/ConnectivityService(  823): calling update connectivity
E/ConnectivityService(  823): updateNetworkInfo()
D/ConnectivityService(  823): ignoring duplicate network state non-change
D/ConnectivityService(  823): ignoring duplicate network state non-change
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): Connected
D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  823): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  823): Validated
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  823):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  823):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  823):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  823): currentScore = 0, newScore = 60
D/ConnectivityService(  823):    accepting network in place of null
D/ConnectivityService(  823): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1476): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  823): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/RCPManagerService(  823): exchangeData() failure , invalid userId
D/ConnectivityService(  823): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  823): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  823): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
V/NetworkStats(  823): updateIfacesLocked()
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
V/NetworkStats(  823): performPollLocked(flags=0x1)
D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/NetworkStatsFactory(  823): UpdateStatsForKnox
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity(  823): Not allowed due to - mEnabled false
D/ConnectivityService(  823): calling update connectivity
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  823): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  823): performPollLocked() took 3ms
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
D/SmartBondingService(  823): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  823):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/ConnectivityService(  823):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  823): calling update connectivity
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
V/NetworkStats(  823): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  823): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
D/NtpTrustedTime(  823): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
D/RCPManagerService(  823): exchangeData() failure , invalid userId
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
E/Zygote  ( 7706): MountEmulatedStorage()
I/libpersona( 7706): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7706): v2
I/libpersona( 7706): KNOX_SDCARD not a persona
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
I/ActivityManager(  823): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7706 uid=10078 gids={50078, 9997} abi=armeabi-v7a
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,E/SMD     (  286): DCD ON
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,I/SELinux ( 7706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,I/SELinux ( 7706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,E/SELinux ( 7706): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  823): exchangeData() failure , invalid userId
,D/RCPManagerService(  823): exchangeData() failure , invalid userId
V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7666): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7706): TimaSignature is unavailable
,D/SecurityLogAgent( 7320): KnoxConfiguration : Current State = 1
D/ActivityThread( 7706): Added TimaKeyStore provider
,D/SecurityLogAgent( 7320): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7320): StateMachine : Current State = 1
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  823): Killing 6787:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/SecurityLogAgent( 7320): StateMachine : Changed Current State = 1
,I/ActivityManager(  823): Killing 6209:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 1710): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): last run: 1455027601283 -- System.currentTimeMillis()-last_run: 8172051
D/com.peel.receiver.ConnectivityActionReceiver( 1710): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): ... skip last_72_check
,I/art     (  823): Explicit concurrent mark sweep GC freed 60704(3MB) AllocSpace objects, 6(161KB) LOS objects, 30% free, 36MB/52MB, paused 1.341ms total 86.821ms
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7706): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  ( 7723): MountEmulatedStorage()
E/Zygote  ( 7723): v2
I/libpersona( 7723): KNOX_SDCARD checking this for 10178
I/libpersona( 7723): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7723 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/ActivityManager(  823): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/libprocessgroup(  823): failed to open /acct/uid_10058/pid_6787/cgroup.procs: No such file or directory
,W/libprocessgroup(  823): failed to open /acct/uid_1000/pid_6209/cgroup.procs: No such file or directory
I/SELinux ( 7723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7723): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7706): onCreate
,D/BadgeProvider( 7706): DatabaseHelper
,D/BadgeProvider( 7706): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7723): TimaSignature is unavailable
,D/ActivityThread( 7723): Added TimaKeyStore provider
,D/BadgeProvider( 7706): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7706): sendNotify, [notify] : null
D/BadgeProvider( 7706): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7706): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7706): update, [UpdateCount] : 1
,D/Launcher.Model( 1482): reloadBadges entered.
,D/ResourcesManager( 7723): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  823): Killing 6808:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ChimeraCfgMgr( 2474): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2474): [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7063): notifyNetworkActivated
,W/libprocessgroup(  823): failed to open /acct/uid_10098/pid_6808/cgroup.procs: No such file or directory
,W/ContextImpl( 7063): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  823): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/hcjo    ( 7063): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7063): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7063): exit::IDLE
D/InitializeManagerStateMachine( 7063): entry::NETWORK_CHECK
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7063): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7063): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7063): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7063): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7063): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7063): entry::SUCCESS
D/hcjo    ( 7063): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  823): MasterInitialState.processMessage what=3
,D/SmartBondingService(  823): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  823): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  823): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  823): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
,I/CLocInfoService(  823): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  823): CLocinfo wifi true 
D/SmartBondingService(  823): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2282): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2160): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7373): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3821): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3821): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/hcjo    ( 7063): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7063): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7063): exit::SUCCESS
D/InitializeManagerStateMachine( 7063): entry::IDLE
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1298): Starting #8
,I/Hs20UtilService( 1298): Message received 5007
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1298): MountReceiver.onReceive - Keep current state
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2(  823): mCursor = null
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7742): MountEmulatedStorage()
E/Zygote  ( 7742): v2
I/libpersona( 7742): KNOX_SDCARD checking this for 10179
I/libpersona( 7742): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7742 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 7742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7742): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7742): TimaSignature is unavailable
,D/ActivityThread( 7742): Added TimaKeyStore provider
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7742): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,E/Zygote  ( 7757): MountEmulatedStorage()
,E/Zygote  ( 7757): v2
I/libpersona( 7757): KNOX_SDCARD checking this for 10082
I/libpersona( 7757): KNOX_SDCARD not a persona
,W/ResourcesManager( 7742): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/ActivityManager(  823): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7757 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  313): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 10.821ms
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.804ms
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.856ms
,I/SELinux ( 7757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7757): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7757): TimaSignature is unavailable
,D/ActivityThread( 7757): Added TimaKeyStore provider
,D/ResourcesManager( 7757): creating new AssetManager and set to /system/app/Books/Books.apk
,D/UMC:Core( 7742): onCreate(): 
,D/USER_AGENT( 7742): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,I/ReaderUtils( 7757): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
,D/[SAMSUNG SMARCART NATIVE]( 7742): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 7742): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7742): ================================================
I/CSTORAGE( 7742):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7742): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7742): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 7742): FINISHED: initialize rv:0
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAV2    ( 7757): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1690): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,I/BooksApp( 7757): Created application version: 3.3.11 (30311)
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  823): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/BooksSync( 7757): Starting books sync, d
,E/HttpOperation( 6554): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at kff.l(PG:132)
E/HttpOperation( 6554): 	at dsf.a(PG:807)
E/HttpOperation( 6554): 	at fhk.a(PG:1126)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 8 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 10 more
,D/ResourcesManager( 2474): creating new AssetManager and set to /system/app/Books/Books.apk
,D/UMC:SecurityUtils( 7742): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7742): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7742): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7742): New Flow
,D/TimaService(  823): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  823): TIMA: in getTimaVersion
I/        (  823): CCM JNI: In ccm_register_for_default_cert
I/        (  823): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  823): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  823): pInitArgs 0x980ff814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  823): &ctx = 0xa00a4c1c
I/TLC_TZ_CCM: (  823): creating new ccm context...
I/TLC_TZ_CCM: (  823): initializing ccm context...
I/TLC_TZ_CCM: (  823): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  823): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  823): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  823): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  823): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  823): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  823): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  823): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  823): Client_Server_Open was called
I/TZ: client_server_communication(  823): IClientServer::IClientServer()
I/TZ: client_server_communication(  823): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  823): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(0) 16
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
D/QSEECOMAPI: ( 1078): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1078): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication( 1078): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  823): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  823): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  823): ctx = 0x9ccc5060, comm = 0x8beffbb0, sendmsg = 0x8be90000, recvmsg = 0x8be94c00
I/TZ_init: (  823): TZ_init: sending initialization request...
I/TZ: client_server_communication(  823): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  823): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/TZ_init: (  823): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  823): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  823): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  823): Calling Communicate()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/TZ_COMMON: tlc_key_db_util: (  823): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  823): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  823): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  823): Calling Communicate()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TLC_TZ_CCM: register for default cert: (  823): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  823): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  823): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  823): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  823): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TZ: client_server_communication(  823): Client_Server_Close was called
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1078): CLOSESWCONN
D/QSEECOMAPI: ( 1078): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1078): QSEECom_shutdown_app, app_id = 3
,I/TZ: client_server_communication(  823): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7742): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7742): TIMA service call for password change success!!
,D/UMC:AdminManager( 7742): init - start
,D/UMC:AdminManager( 7742): loadAdmins
,E/SQLiteLog( 7757): (284) automatic index on view_volumes(volume_id)
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/UMC:AdminManager( 7742): startPolicyHandlers
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
I/UMC:TestPolicyHandler( 7742): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7742): init - end
,V/UMC:AlarmHandler( 7742): Enter loadList
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6554): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at kff.l(PG:132)
E/HttpOperation( 6554): 	at ieo.a(PG:43)
E/HttpOperation( 6554): 	at iep.a(PG:93)
E/HttpOperation( 6554): 	at fhn.a(PG:59)
E/HttpOperation( 6554): 	at lex.a(PG:85)
E/HttpOperation( 6554): 	at lex.b(PG:132)
E/HttpOperation( 6554): 	at fhk.a(PG:1146)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 12 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 14 more
,E/ExperimentLoader( 6554): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6554): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6554): 	at kfv.a(PG:65)
E/ExperimentLoader( 6554): 	at kff.u(PG:385)
E/ExperimentLoader( 6554): 	at kfb.a(PG:29)
E/ExperimentLoader( 6554): 	at kff.l(PG:132)
E/ExperimentLoader( 6554): 	at ieo.a(PG:43)
E/ExperimentLoader( 6554): 	at iep.a(PG:93)
E/ExperimentLoader( 6554): 	at fhn.a(PG:59)
E/ExperimentLoader( 6554): 	at lex.a(PG:85)
E/ExperimentLoader( 6554): 	at lex.b(PG:132)
E/ExperimentLoader( 6554): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6554): 	at fhk.a(PG:908)
E/ExperimentLoader( 6554): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6554): 	at ihi.a(PG:22)
E/ExperimentLoader( 6554): 	at kft.a(PG:91)
E/ExperimentLoader( 6554): 	at kfv.a(PG:62)
E/ExperimentLoader( 6554): 	... 12 more
E/ExperimentLoader( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6554): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6554): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6554): 	at ihi.a(PG:19)
E/ExperimentLoader( 6554): 	... 14 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/GSLBManager( 7742): migrateStoredUrlFromOldPref
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/GSLBManager( 7742): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7742): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7742): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7742): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7742): isContainer : 0
,W/LicenseLogService(  823): log() failed
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/EnterpriseDeviceManagerService(  823): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7742): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7742): isContainer : 0
,D/UMC:UMCAdmin( 7742): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7742): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,D/QuickStartReceiver( 7742): Msg Id : 2
D/QuickStartReceiver( 7742): model : SM-G900F
D/QuickStartReceiver( 7742): id : 100
,I/Hs20UtilService( 1298): Starting #9
,I/Hs20UtilService( 1298): Message received 5007
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1298): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1298): Starting #10
,I/Hs20UtilService( 1298): Message received 5007
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 23702(1419KB) AllocSpace objects, 8(648KB) LOS objects, 40% free, 17MB/29MB, paused 473us total 31.356ms
D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1298): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7228): 
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1298): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1298): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1298): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1298): Starting #11
,I/Hs20UtilService( 1298): Message received 5007
,D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1298): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  823): callSECApi what=220
,D/WifiStateMachine(  823): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PCWCLIENTTRACE_PushUtil( 6711): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6711): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6711): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6711): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DIAGMON_AGENT( 7439): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7439): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 1690): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,D/PowerManagerService(  823): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=823
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 1690): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7757): null auth token
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/X       (  823): broadcastSiopLevelIntent:: currentSiopLevel = 0
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ContentApp( 1223):  LEVEL : 0
,I/System.out( 7757): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 7757): (HTTPLog)-Static: isShipBuild true
,I/System.out( 7757): (HTTPLog)-Thread-1282-530618724: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/FOTA_Client( 7465): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7465): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7465): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7465): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,E/HttpOperation( 6554): [getaccountstatus] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at ixd.a(PG:248)
E/HttpOperation( 6554): 	at ixd.b(PG:206)
E/HttpOperation( 6554): 	at ixd.a(PG:175)
E/HttpOperation( 6554): 	at fig.a(PG:78)
E/HttpOperation( 6554): 	at lex.a(PG:85)
E/HttpOperation( 6554): 	at lex.b(PG:132)
E/HttpOperation( 6554): 	at fhk.a(PG:1146)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 12 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 14 more
,E/EsSyncAdapterService( 6554): Sync failure
E/EsSyncAdapterService( 6554): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6554): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6554): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6554): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6554): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6554): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6554): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6554): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6554): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6554): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6554): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6554): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6554): 	... 10 more
E/EsSyncAdapterService( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6554): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6554): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6554): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6554): 	... 12 more
E/EsSyncAdapterService( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6554): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6554): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6554): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6554): 	... 14 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/FOTA_Client( 7465): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/KLMS-2.4.503: ( 7480): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7480): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1455035774558
,I/KLMS-2.4.503: ( 7480): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7480): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7480): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7480): NetworkChangeOperations(): uploadRequestLog().START 
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 59697, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7480): StateImplV2(): networkChangeListener().END
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7500): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  823): mCursor = null
,E/WifiStateMachine(  823): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  823): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  823): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  823): identical MTU - not setting
D/ConnectivityService(  823): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  823): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,E/WifiStateMachine(  823): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
V/        (  280): QcRouteController
,D/SmartBondingService(  823): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  823): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
D/SmartBondingService(  823): getSBEnabled() enabled =false
,V/        (  280): QcRouteController
,W/NetworkManagementService(  823): route cmd failed: 
W/NetworkManagementService(  823): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  823): '
W/NetworkManagementService(  823): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  823): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  823): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  823): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  823): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  823): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  823): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  823): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  823): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  823): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  823): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  823): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  823): calling update connectivity
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  823): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
D/ConnectivityService(  823): calling update connectivity
,D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  823):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  823): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5131): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6749): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6749): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6749): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6749): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6749): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6749): [SCU] == networkStateCheck == true
I/SA      ( 6749): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6749): isChinaCountryCode : false
I/SA      ( 6749): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6749): [OR] == networkStateCheck true ==
,I/SA      ( 6749): [OR] GetMyCountryZoneTask
,I/SA      ( 6749): [OR] onReceive END
,I/SA      ( 6749): [SRS] prepareGetMyCountryZone
,I/SA      ( 6749): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6749): [SSP] query invoked
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 7517): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7517): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6749): [TPMU] GetMccFromDB : null
I/SA      ( 6749): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6749): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7534): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7534): premStatus:2
,I/KnoxUsageLogPro( 7534): isEulaShown : false
I/KnoxUsageLogPro( 7534): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6749): fail readDirectory() errno=2
,D/Headlines( 5484): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5484): getCountryCode(): countryCode = DE
,D/Headlines( 5484): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5484): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5484): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5484): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5484): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5484): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5484): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7630): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7630): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7630): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  823): exchangeData() failure , invalid userId
,D/RCPManagerService(  823): exchangeData() failure , invalid userId
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7320): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7320): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7320): StateMachine : Current State = 1
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7320): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1710): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): last run: 1455027601283 -- System.currentTimeMillis()-last_run: 8173485
D/com.peel.receiver.ConnectivityActionReceiver( 1710): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1710): ... skip last_72_check
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2474): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2474): [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7063): AutoUpdateManager:IDLE:execute
,E/TranscodeReceiver( 7083): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7083):  SIOP_LEVEL: 0
,D/InitializeManagerStateMachine( 7063): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7063): exit::IDLE
D/InitializeManagerStateMachine( 7063): entry::NETWORK_CHECK
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7063): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7063): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7063): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7063): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7063): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7063): entry::SUCCESS
D/hcjo    ( 7063): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/qtaguid ( 7757): Untagging socket 34
D/hcjo    ( 7063): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7063): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7063): exit::SUCCESS
D/InitializeManagerStateMachine( 7063): entry::IDLE
W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
,W/ApiaryClient( 7757): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3140305200382339710&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1690): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  823): SIOP:: AP = 420, PST = 440, CUR = 300
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7228): 
,I/SA      ( 6749): [RC New] Execute method=[GET] start
,I/SA      ( 6749): [RC New] Security=[true]
,I/System.out( 6749): Thread-1100(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/AlarmManager(  823): waitForAlarm result :4
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 6749): Thread-1100(ApacheHTTPLog):isShipBuild true
,I/System.out( 6749): Thread-1100(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 7228): 
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1690): Connected
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1690): Message class com.google.f.a.a.p
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7457): wlan0: sending IPv6 Router Solicitation
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,I/SA      ( 6749): [RC New] [v2liruge] api execute + 647
,I/SA      ( 6749): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
I/System.out( 6749): AsyncTask #1 calls detatch()
E/HttpHelper( 7757): null auth token
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,I/qtaguid ( 7757): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/SA      ( 6749): [ODM] saveOpenData( GEO_IP, PL )
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
,W/ApiaryClient( 7757): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3140305200382339710&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  823): Explicit concurrent mark sweep GC freed 39248(2MB) AllocSpace objects, 10(485KB) LOS objects, 30% free, 36MB/52MB, paused 1.390ms total 99.675ms
,I/SA      ( 6749): [OCP] update openData : PL
,I/SA      ( 6749): [TPMU] getNetworkMcc : 
,I/SA      ( 6749): [SCU] saveMccToPreferece Start
,I/SA      ( 6749): [SCU] RegionMCC : 260
I/SA      ( 6749): [SSP] query invoked
,I/SA      ( 6749): [TPMU] GetMccFromDB : null
,I/SA      ( 6749): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6749): [SCU] saveMccToPreferece End
,I/SA      ( 6749): [RC New] executeRequest [v2liruge] end. 832
I/SA      ( 6749): [RC New] Execute end
I/SA      ( 6749): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6749): [OR] GetMyCountryZoneTask Success
,D/WearableService( 4894): callingUid 10012, callindPid: 4894
,D/ResourcesManager( 7373): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7373): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7373): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7373): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7373): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7373): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7373): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7373): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7373): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 7373): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7373): Conditions not met for autocaching.
,I/MusicLeanback( 7373): Stop autocaching.
,E/ActivityThread( 7373): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@91c2742 that was originally bound here
E/ActivityThread( 7373): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@91c2742 that was originally bound here
E/ActivityThread( 7373): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7373): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7373): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7373): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7373): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7373): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7373): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7373): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7373): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7373): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7373): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7373): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7373): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7373): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7373): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7373): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7373): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7373): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7373): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7373): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7373): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7373): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7373): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7373): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7373): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SMD     (  286): DCD ON
,I/WifiStateMachine(  823): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  823): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7757): null auth token
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
,W/ApiaryClient( 7757): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3140305200382339710&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GAV4    ( 7568): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  249): id=15 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=15 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  823): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 823) eventTime = 96211
,D/PowerManagerService(  823): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=823 (0x0)
,D/PowerManagerService(  823): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=823, ws=WorkSource{10059}) (elapsedTime=3472)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/BooksSync( 7757): Soft error
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3140305200382339710&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7757): Headers suppressed
E/BooksSync( 7757): 
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7757): Sync error
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-3140305200382339710&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7757): Headers suppressed
E/BooksSync( 7757): 
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7757): Finished books sync
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  823): Killing 6844:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/ActivityManager(  823): Killing 6864:com.vlingo.midas/u0a33 (adj 15): bgCount ##42
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62726, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  823): mCursor = null
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  823): failed to open /acct/uid_10033/pid_6864/cgroup.procs: No such file or directory
W/libprocessgroup(  823): failed to open /acct/uid_10099/pid_6844/cgroup.procs: No such file or directory
,I/GAV2    ( 7757): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  286): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6711): mConnectivityHandler : connected
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6711): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6711): ================================================
,I/CSTORAGE( 6711):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6711): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6711): [GetString-S]
E/art     ( 6711): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6711): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6711): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6711): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6711): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6711): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6711): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7457): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): Test app app.js loaded
I/jxcore-log( 7228): 
,I/chromium( 7228): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Bluetooth MAC address: B0:C5:59:3F:75:69, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7228): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fa30756 added. We now have 1 listener(s)
,I/jxcore-log( 7228): BLE advertisement is supported
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): TAP version 13
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 1 publicKeysToNotify cannot be null
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 2 ecdhForLocalDevice cannot be null
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 3 secondsUntilExpiration out of range.
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 4 secondsUntilExpiration out of range.
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 5 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 6 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 7 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 8 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 9 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 10 should throw
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 11 Preamble expiration must be a 64 bit integer
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons expiration out of range lower
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 12 Expiration out of range
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons expiration out of range lower
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 13 Expiration out of range
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons no beacons returns null
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 14 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 15 Malformed encrypted beacon key ID
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 16 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 17 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 18 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 19 should be equal
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 20 (unnamed assert)
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
I/jxcore-log( 7228): # setup
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ok 21 (unnamed assert)
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): # teardown
I/jxcore-log( 7228): 
,E/SMD     (  286): DCD ON
,I/dhcpcd  ( 7457): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7457): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7063): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7063): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7063): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7063): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7063): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7063): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7063): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7063): entry::IDLE
,D/PackageManager(  823): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  823): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,E/Zygote  ( 7860): MountEmulatedStorage()
,E/Zygote  ( 7860): v2
I/libpersona( 7860): KNOX_SDCARD checking this for 10034
I/libpersona( 7860): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7860 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/SELinux ( 7860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 1482): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1482): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1482): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1482): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/RegisteredServicesCache( 1470): empty dynamic service
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 1482): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1482): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1482): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  823): mCursor = null
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider( 7860): TimaSignature is unavailable
,D/ActivityThread( 7860): Added TimaKeyStore provider
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/PreloadUpdateManagerStateMachine( 7063): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7063): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7063): entry::CHECK_TIMEOUT_FOR_UPDATE
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/hcjo    ( 7063): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7063): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/PreloadUpdateManagerStateMachine( 7063): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7063): entry::IDLE
,I/FeatureConfig( 7860): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  823): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  823): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  823): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,V/AlarmManager(  823): waitForAlarm result :4
,D/ResourcesManager(  823): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  823): stay LED for fully charged
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
,I/MotionRecognitionService(  823): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3238): Disconnected process message: 10
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,I/PowerManagerService(  823): [PWL] Off : 30s ago
I/PowerManagerService(  823): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  823): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  823): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=823, ws=WorkSource{10012}) (elapsedTime=96)
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/SSRM:m  (  823): SIOP:: AP = 410, PST = 437, CUR = 300,
,W/ResourcesManager( 7860): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/Watchdog(  823): !@Sync 3
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SMD     (  286): DCD ON
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/AlarmManager(  823): waitForAlarm result :4
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  823): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7902 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 7902): MountEmulatedStorage()
,E/Zygote  ( 7902): v2
,I/libpersona( 7902): KNOX_SDCARD checking this for 10035
I/libpersona( 7902): KNOX_SDCARD not a persona
,I/SELinux ( 7902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7902): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7902): TimaSignature is unavailable
,D/ActivityThread( 7902): Added TimaKeyStore provider
,D/ResourcesManager( 7902): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7935): MountEmulatedStorage()
E/Zygote  ( 7935): v2
I/libpersona( 7935): KNOX_SDCARD checking this for 10017
I/libpersona( 7935): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7935 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 7935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 7935): TimaSignature is unavailable
,D/ActivityThread( 7935): Added TimaKeyStore provider
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 7935): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/Finsky  ( 6584): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6584): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6584): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  823): Killing 6907:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/libprocessgroup(  823): failed to open /acct/uid_10003/pid_6907/cgroup.procs: No such file or directory
,D/BluetoothManager( 7902): getConnectedDevices
,D/-----SIC-----( 7902): ------------------skip uv
,D/-----SIC-----( 7902): ------------------skip SPO2
D/-----SIC-----( 7902): ------------------skip TGH
,I/SecureStorage( 7935): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  328): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 7935
I/SecureStorage(  328): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7902): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7902): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7902): decode(33, 19359868, 4230)
,V/MediaPlayerService(  292): decode(30, 19359868, 4230)
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
D/AdaptiveEventManager( 1170): M updateContainers()
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
V/MediaPlayerService(  292): wait for prepare
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor,
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,E/Zygote  ( 7980): MountEmulatedStorage()
I/libpersona( 7980): KNOX_SDCARD checking this for 10048
E/Zygote  ( 7980): v2
I/libpersona( 7980): KNOX_SDCARD not a persona
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,I/ActivityManager(  823): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7980 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
,I/SELinux ( 7980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/AudioPlayer(  292): First fillBuffer call!!
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,I/SELinux ( 7980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
E/SELinux ( 7980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 8, 0, 0)
I/ActivityManager(  823): Killing 6929:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7902): decode(35, 19213040, 15440)
V/MediaPlayerService(  292): decode(29, 19213040, 15440)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
I/ActivityManager(  823): Killing 6916:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##42
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(29, 19213040, 15440)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,D/TimaKeyStoreProvider( 7980): TimaSignature is unavailable
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/ActivityThread( 7980): Added TimaKeyStore provider
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  292): wait for playback complete
,D/ResourcesManager( 7980): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,W/ResourcesManager( 7980): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7980): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/DatabaseUtils(  823): Writing exception to parcel
E/DatabaseUtils(  823): java.lang.NullPointerException: key == null
E/DatabaseUtils(  823): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  823): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  823): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  823): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  823): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  823): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ResourcesManager( 7980): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7980): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7980): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7980): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7980): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(36, 19257568, 9226)
,V/MediaPlayerService(  292): decode(30, 19257568, 9226)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
,V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19257568, 9226)
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
,I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 6, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
,I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(37, 19364180, 4890)
V/MediaPlayerService(  292): decode(30, 19364180, 4890)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l(),
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
,V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb1578290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
,V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 5, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 2, 0, 0)
,V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 7, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
W/libprocessgroup(  823): failed to open /acct/uid_1000/pid_6929/cgroup.procs: No such file or directory
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
,I/OggExtractor(  292): ~OggExtractor ++
W/libprocessgroup(  823): failed to open /acct/uid_10020/pid_6916/cgroup.procs: No such file or directory
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(38, 19290344, 17329)
,V/MediaPlayerService(  292): decode(30, 19290344, 17329)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  292): notify(0xb0724dd0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 1, 0, 0)
,V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(39, 19190536, 6644)
V/MediaPlayerService(  292): decode(30, 19190536, 6644)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): addBatteryData
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(40, 19266876, 23389)
V/MediaPlayerService(  292): decode(30, 19266876, 23389)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
,I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7902): decode(41, 19156232, 8154)
V/MediaPlayerService(  292): decode(29, 19156232, 8154)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(29, 19156232, 8154)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(42, 19129712, 4804)
V/MediaPlayerService(  292): decode(30, 19129712, 4804)
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
,V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
,V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/SensorService(  823): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  823): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/SensorService(  823): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 200, 973, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
,D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 6, 0, 0)
I/AudioPlayer(  292): First fillBuffer call!!
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(43, 19099164, 9400)
V/MediaPlayerService(  292): decode(30, 19099164, 9400)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
,V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  292): notify(0xb1578290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb1578290, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
V/MediaPlayer( 7902): decode(49, 19172584, 4112)
,V/MediaPlayerService(  292): decode(35, 19172584, 4112)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(35, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(36) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
,I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 811298076, value : 198833648
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 811298076, value : 198833648
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0724dd0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start,
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
D/Spen    ( 7980): SpenSdk version level = 55
,D/Spen    ( 7980): SpenSdk jar version = 3.0.238
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0724dd0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mRe,achedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
,I/OggExtractor(  292): ~OggExtractor --
,D/Spen    ( 7980): SpenSdk apk version = 3.0.238
,D/Spen    ( 7980): Server UPDATE Check
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(44, 19307764, 52024)
,V/MediaPlayerService(  292): decode(31, 19307764, 52024)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(31, 19307764, 52024)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(29) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
,I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,W/linker  ( 7980): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
D/SPenError( 7980): JNI_OnLoad
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
,E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
D/JNI_Bitmap( 7980): Init .. Done
,D/SPenSpiDecoder( 7980): JNI_OnLoad .. Done
D/SPenError( 7980): JNI_OnLoad Success
,D/PluginManager( 7980): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager( 7980): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni( 7980): JNI_OnLoad
,D/Init_SPenSdk_Jni( 7980): AndroidSDK: 21
,D/Init_SPenSdk_Jni( 7980): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni( 7980): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni( 7980): JNI_OnLoad .. Done
,D/Model_ObjectImage_Jni( 7980): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni( 7980): JNI_OnLoad .. Done
,D/Model_ObjectContainer_Jni( 7980): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni( 7980): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni( 7980): check build type eng[0]
,D/Model_NoteDoc_Jni( 7980): JNI_OnLoad .. Done
,D/Model_NoteFile_Jni( 7980): JNI_OnLoad .. Done
,D/Model_ObjectUtil_Jni( 7980): JNI_OnLoad .. Done
D/Model   ( 7980): OnLoad class Done
,D/spe_log ( 7980): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library( 7980): Draw Engine JNI_OnLoad enter!!
,D/SPen_Library( 7980): Canvas JNI_OnLoad enter!!
,D/SPen_Library( 7980): Canvas JNI_OnLoad Success
,D/SPen_Library( 7980): TextView JNI_OnLoad enter!!
,D/SPen_Library( 7980): TextView JNI_OnLoad Success
,D/SPen_Library( 7980): Text JNI_OnLoad enter!!
D/SPen_Library( 7980): Text JNI_OnLoad Success
D/SPen_Library( 7980): FontManager JNI_OnLoad enter!!
,D/SPen_Library( 7980): FontManager JNI_OnLoad Success
D/SPen_Library( 7980): CapturePage JNI_OnLoad enter!!
,D/SPen_Library( 7980): CapturePage JNI_OnLoad Success
D/SPen_Library( 7980): Multi JNI_OnLoad enter!!
,D/SPen_Library( 7980): Multi JNI_OnLoad Success
,D/SPen_Library( 7980): Draw Engine JNI_OnLoad Success
,D/SPen_Library( 7980): Brush JNI_OnLoad enter!!
,D/SPen_Library( 7980): Brush JNI_OnLoad Success
,D/SPen_Library( 7980): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library( 7980): ChineseBrush JNI_OnLoad Success
,D/SPen_Library( 7980): InkPen JNI_OnLoad enter!!
,D/SPen_Library( 7980): InkPen JNI_OnLoad Success
,D/SPen_Library( 7980): Marker JNI_OnLoad enter!!
,D/SPen_Library( 7980): Marker JNI_OnLoad Success
,D/SPen_Library( 7980): Pencil JNI_OnLoad enter!!
,D/SPen_Library( 7980): Pencil JNI_OnLoad Success
,D/SPen_Library( 7980): NativePen JNI_OnLoad enter!!
,D/SPen_Library( 7980): NativePen JNI_OnLoad Success
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,D/SPen_Library( 7980): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library( 7980): MontblancFountainPen JNI_OnLoad Success
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1578150, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7902): decode(45, 19172584, 4112)
,V/MediaPlayerService(  292): decode(30, 19172584, 4112)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
D/SPen_Library( 7980): MontblancCalligraphyPen JNI_OnLoad enter!!
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
D/SPen_Library( 7980): MontblancCalligraphyPen JNI_OnLoad Success
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb07249c0, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
,I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
,I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
D/SPen_Library( 7980): MagicPen JNI_OnLoad enter!!
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/SPen_Library( 7980): MagicPen JNI_OnLoad Success
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7902): decode(46, 19235660, 21825)
V/MediaPlayerService(  292): decode(31, 19235660, 21825)
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
D/SPen_Library( 7980): ObliquePen JNI_OnLoad enter!!
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(31, 19235660, 21825)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(29) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SPen_Library( 7980): ObliquePen JNI_OnLoad Success
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/SPen_Library( 7980): FountainPen JNI_OnLoad enter!!
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 6, 0, 0)
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,D/SPen_Library( 7980): FountainPen JNI_OnLoad Success
,D/Spen    ( 7980): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni( 7980): SPenSdk_init2
D/Init_SPenSdk( 7980): Init - screen_width = 1080, screen_height = 1920, maxCacheSize = 5 M
,D/Init_SPenSdk( 7980): Total S Pen SDK Directory Size = 0
,D/Spen    ( 7980): initialize complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7902): decode(47, 19134596, 21552)
,V/MediaPlayerService(  292): decode(30, 19134596, 21552)
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 200, 973, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb1b1e060, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
,V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb1b1e060, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb1b1e060, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb1b1e060, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
,I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
D/NearbySource( 7980): Nearby Source Create!
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
D/NearbyContext( 7980): Nearby Context Create!
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7902): decode(48, 19228560, 7017)
V/MediaPlayerService(  292): decode(29, 19228560, 7017)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
,V/StagefrightPlayer(  292): setDataSource(29, 19228560, 7017)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
D/FactoryTest( 5823): Not factory mode
D/FactoryTest( 5823): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5823): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5823): still no open session command from host, so toast
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,W/ContextImpl( 5823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 5823): Timeline: Activity_launch_request id:com.android.settings time:105522
E/PersonaManagerService(  823): inState():  stateMachine is null !!
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 200, 973, 0)
V/AudioCache(  292): ignored
W/ActivityManager(  823): mDVFSHelper.acquire()
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,E/MTPRx   ( 5823): started activity for popup
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,I/SQLiteSecureOpenHelper( 3574): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3574): getDatabaseLocked(b,b,pwd)...
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0809290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
,I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7980): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 7980): Samsung link source created
,D/SLinkClient( 7980): query devices()
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  823): Start proc com.samsung.android.sdk.samsunglink for content provider com.samsung.android.sdk.samsunglink/com.mfluent.asp.datamodel.ASPMediaStoreProvider: pid=8065 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 8065): MountEmulatedStorage()
I/libpersona( 8065): KNOX_SDCARD checking this for 10042
E/Zygote  ( 8065): v2
I/libpersona( 8065): KNOX_SDCARD not a persona
,I/SELinux ( 8065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager( 5823): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/SELinux ( 8065): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SecureStorage(  328): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  328): [INFO]: SPID(0x00000005)PID: 7935, TID: 7946
,W/ResourcesManager( 5823): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5823): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5823): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 5823): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5823): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5823): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5823): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8065): TimaSignature is unavailable
,D/ActivityThread( 8065): Added TimaKeyStore provider
,D/ResourcesManager( 8065): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,E/SettingsReceiverActivity( 5823): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  823): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  823): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@25f34db3 attribute=null, token = android.os.BinderProxy@16edfa7c
,D/ContactProvider( 7980): getAllContactInfoList Start
,W/ResourcesManager( 8065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter(  823): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager( 8065): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WifiDisplayAdapter(  823): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,I/UpdateIcingCorporaServi( 1590): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 5823): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/Zygote  ( 8084): MountEmulatedStorage()
E/Zygote  ( 8084): v2
,I/libpersona( 8084): KNOX_SDCARD checking this for 10075
I/libpersona( 8084): KNOX_SDCARD not a persona
,D/SettingsReceiverActivity( 5823): dev.kiessupport is : TRUE
I/ActivityManager(  823): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8084 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ContactProvider( 7980): getAllContactInfoList End
,I/ActivityManager(  823): Killing 6971:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/ActivityManager(  823): Killing 6955:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##42
,I/syncContacts( 7980): thread: 1295, sync time = 102
,D/Activity( 5823): performCreate Call secproduct feature valuefalse
,D/Activity( 5823): performCreate Call debug elastic valuetrue
D/TimaKeyStoreProvider( 8084): TimaSignature is unavailable
,D/ActivityThread( 8084): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ActivityManager(  823): post active user change for 0
D/KnoxTimeoutHandler(  823): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  823): handleActiveUserChange for user 0
,D/ResourcesManager( 8084): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/UpdateIcingCorporaServi( 1590): UpdateCorporaTask done [took 72 ms] updated apps [took 72 ms] 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 7228): Timeline: Activity_idle id: android.os.BinderProxy@2967e609 time:105869
,D/FileShare-Server( 8084): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8100): MountEmulatedStorage()
E/Zygote  ( 8100): v2
I/libpersona( 8100): KNOX_SDCARD checking this for 1000
I/libpersona( 8100): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8100 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  823): Killing 6987:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/SELinux ( 8100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  823): failed to open /acct/uid_10112/pid_6955/cgroup.procs: No such file or directory
,W/libprocessgroup(  823): failed to open /acct/uid_10118/pid_6971/cgroup.procs: No such file or directory
,I/SELinux ( 8100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8100): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8100): TimaSignature is unavailable
,D/ActivityThread( 8100): Added TimaKeyStore provider
,W/libprocessgroup(  823): failed to open /acct/uid_1000/pid_6987/cgroup.procs: No such file or directory
,D/ResourcesManager( 8100): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,W/System.err( 8065): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
,W/System.err( 8065): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 8065): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 8065): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 8065): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 8065): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 8065): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 8065): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 8065): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 8065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 8065): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 8065): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 8065): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8065): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8065): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8065): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8065): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8065): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SL_DEBUG( 8065): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 8065): isLoggable:: SL_DEBUG_EXIST = false
,D/ShortcutReceiver( 8100):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SLinkClient( 7980): queryDevices : cursor.getCount() = [ 0 ]
,D/SLinkClient( 7980): onStorageUpdated(), uri = [ slink://slink ]
,D/PackageBroadcastService( 2474): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/SLinkClient( 7980): SlinkBackgroundJob: slink wake up ok!
,I/SecureStorage( 7935): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7935): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PeopleContactsSync( 2474): CP2 sync disabled
,I/SecSQLiteOpenHelper( 7902): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 7902): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7902): Open platform.db in secure mode
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SecSQLiteDatabase( 7902): Android Version: 5.0
D/SecSQLiteDatabase( 7902): Load library secsqlite.so for Android 5.0
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8065): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8065): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,V/Transcoder( 8065): Transcoder(0xaf80a830)::constructor
V/Transcoder( 8065): addObitRecipient
V/TMI-JNI ( 8065): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,I/SecSQLiteDatabase( 7902): openSecureDatabase...
,I/SecSQLiteDatabase( 7902): private openSecureDatabase...
I/SecSQLiteConnectionPool( 7902): OpenSecure
I/SecSQLiteConnectionPool( 7902): OpenSecure with password
I/SecSQLiteConnectionPool( 7902): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7902): ...private openSecureDatabase
I/SecSQLiteDatabase( 7902): ...openSecureDatabase
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SecSQLiteOpenHelper( 7902): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7902): ...getDatabaseLocked(b,b,pwd)
,I/ActivityManager(  823): Killing 7028:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7902): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7902): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7902): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7902): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7902): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7902): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7902): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7902): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  823): failed to open /acct/uid_10166/pid_7028/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6,
,I/Atfwd_Daemon(  320): result : -1 ,	, ,Init step :2 ,	 ,qmiErrorCode: 0
,W/ActivityManager(  823): mDVFSHelper.release(),
,E/SMD     (  286): DCD ON
,I/GAV3    ( 7902): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  823): SIOP:: AP = 390, PST = 432, CUR = 300
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  823): waitForAlarm result :4
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  823): stay LED for fully charged
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
I/MotionRecognitionService(  823): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/PowerManagerService(  823): [PWL] Off : 50s ago
,D/SSRM:m  (  823): SIOP:: AP = 350, PST = 419, CUR = 300
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  823): waitForAlarm result :4
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/art     (  823): Explicit concurrent mark sweep GC freed 55180(3MB) AllocSpace objects, 15(305KB) LOS objects, 30% free, 36MB/52MB, paused 1.259ms total 103.634ms
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6584): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6584): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6584): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
,I/MotionRecognitionService(  823): setPowerConnected  = true
,D/BatteryService(  823): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  823): !@Sync 4
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  823): SIOP:: AP = 340, PST = 404, CUR = 300
,D/X       (  823): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1223):  LEVEL : -1
,E/TranscodeReceiver( 7083): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7083):  SIOP_LEVEL: -1
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  823): waitForAlarm result :8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  823): SIOP:: AP = 330, PST = 388, CUR = 300
,V/AlarmManager(  823): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): stay LED for fully charged
,D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
I/MotionRecognitionService(  823): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6584): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6584): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6584): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  823): [PWL] Off : 75s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  823): waitForAlarm result :4
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7757): Starting books sync, d
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7757): null auth token
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6554): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at kff.l(PG:132)
E/HttpOperation( 6554): 	at dsf.a(PG:807)
E/HttpOperation( 6554): 	at fhk.a(PG:1126)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 8 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 10 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
W/ApiaryClient( 7757): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5165013277696136088&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6554): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at kff.l(PG:132)
E/HttpOperation( 6554): 	at ieo.a(PG:43)
E/HttpOperation( 6554): 	at iep.a(PG:93)
E/HttpOperation( 6554): 	at fhn.a(PG:59)
E/HttpOperation( 6554): 	at lex.a(PG:85)
E/HttpOperation( 6554): 	at lex.b(PG:132)
E/HttpOperation( 6554): 	at fhk.a(PG:1146)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 12 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 14 more
E/ExperimentLoader( 6554): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6554): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6554): 	at kfv.a(PG:65)
E/ExperimentLoader( 6554): 	at kff.u(PG:385)
E/ExperimentLoader( 6554): 	at kfb.a(PG:29)
E/ExperimentLoader( 6554): 	at kff.l(PG:132)
E/ExperimentLoader( 6554): 	at ieo.a(PG:43)
E/ExperimentLoader( 6554): 	at iep.a(PG:93)
E/ExperimentLoader( 6554): 	at fhn.a(PG:59)
E/ExperimentLoader( 6554): 	at lex.a(PG:85)
E/ExperimentLoader( 6554): 	at lex.b(PG:132)
E/ExperimentLoader( 6554): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6554): 	at fhk.a(PG:908)
E/ExperimentLoader( 6554): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6554): 	at ihi.a(PG:22)
E/ExperimentLoader( 6554): 	at kft.a(PG:91)
E/ExperimentLoader( 6554): 	at kfv.a(PG:62)
E/ExperimentLoader( 6554): 	... 12 more
E/ExperimentLoader( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6554): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6554): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6554): 	at ihi.a(PG:19)
E/ExperimentLoader( 6554): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6554): [getaccountstatus] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at ixd.a(PG:248)
E/HttpOperation( 6554): 	at ixd.b(PG:206)
E/HttpOperation( 6554): 	at ixd.a(PG:175)
E/HttpOperation( 6554): 	at fig.a(PG:78)
E/HttpOperation( 6554): 	at lex.a(PG:85)
E/HttpOperation( 6554): 	at lex.b(PG:132)
E/HttpOperation( 6554): 	at fhk.a(PG:1146)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 12 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 14 more
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/EsSyncAdapterService( 6554): Sync failure
E/EsSyncAdapterService( 6554): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6554): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6554): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6554): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6554): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6554): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6554): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6554): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6554): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6554): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6554): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6554): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6554): 	... 10 more
E/EsSyncAdapterService( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6554): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6554): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6554): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6554): 	... 12 more
E/EsSyncAdapterService( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6554): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6554): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6554): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6554): 	... 14 more
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 123279, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  823): mCursor = null
,E/SQLiteLog( 1690): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  823): SIOP:: AP = 330, PST = 377, CUR = 300
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7757): null auth token
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
,W/ApiaryClient( 7757): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5165013277696136088&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 33936(2MB) AllocSpace objects, 20(1620KB) LOS objects, 39% free, 17MB/29MB, paused 775us total 66.294ms
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1690): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7757): null auth token
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  823): stay LED for fully charged
D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  823): Plugged
I/MotionRecognitionService(  823): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
,W/ApiaryClient( 7757): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5165013277696136088&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7757): Soft error
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5165013277696136088&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7757): Headers suppressed
E/BooksSync( 7757): 
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7757): Sync error
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5165013277696136088&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7757): Headers suppressed
E/BooksSync( 7757): 
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7757): Finished books sync
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126653, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  823): mCursor = null
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  823): !@Sync 5
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  823): SIOP:: AP = 320, PST = 368, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,V/AlarmManager(  823): waitForAlarm result :4
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): stay LED for fully charged
D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
I/MotionRecognitionService(  823): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1690): Vacuum at: now=1455035855260 tag=VacuumService
,I/GoogleURLConnFactory( 1690): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/SSRM:m  (  823): SIOP:: AP = 320, PST = 359, CUR = 300
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1690): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1690): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1690): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1690): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1690): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1690): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1690): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1690): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1690): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1690): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/System.out( 1690): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1690): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1690): (HTTPLog)-Thread-203-889883775: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1690): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1690, getuid(): 10012
,I/qtaguid ( 1690): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1690, getuid(): 10012
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1690): No account for auth token provided
,I/qtaguid ( 1690): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1690, getuid(): 10012
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1690): No account for auth token provided
,D/Finsky  ( 6584): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6584): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6584): [1] 5.onFinished: Scheduling replication attempt 5.
,I/qtaguid ( 1690): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1690, getuid(): 10012
,W/Uploader( 1690): No account for auth token provided
,I/qtaguid ( 1690): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1690, getuid(): 10012
,W/Uploader( 1690): No account for auth token provided
,I/qtaguid ( 1690): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1690, getuid(): 10012
,W/Uploader( 1690):  no longer exists, so no auth token.
,I/qtaguid ( 1690): Tagging socket 55 with tag 120100000000{4609,0} uid -1, pid: 1690, getuid(): 10012
,E/SQLiteLog( 1690): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  823): [PWL] Off : 105s ago,
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  823): waitForAlarm result :4
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
,I/MotionRecognitionService(  823): setPowerConnected  = true
,D/BatteryService(  823): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  823): SIOP:: AP = 310, PST = 352, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  823): !@Sync 6
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  823): SIOP:: AP = 310, PST = 341, CUR = 300
,V/AlarmManager(  823): waitForAlarm result :4
,I/art     (  823): Explicit concurrent mark sweep GC freed 48246(2MB) AllocSpace objects, 32(967KB) LOS objects, 30% free, 36MB/52MB, paused 1.932ms total 142.789ms
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6584): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6584): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6584): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  286): DCD ON
,V/AlarmManager(  823): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  823): SIOP:: AP = 310, PST = 331, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  823): [PWL] Off : 140s ago
,V/AlarmManager(  823): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate,
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  823): SIOP:: AP = 310, PST = 323, CUR = 300
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1690): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6554): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at kff.l(PG:132)
E/HttpOperation( 6554): 	at dsf.a(PG:807)
E/HttpOperation( 6554): 	at fhk.a(PG:1126)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 8 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SQLiteLog( 1690): (10) POSIX Error : 11 SQLite Error : 3850
,E/HttpOperation( 6554): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at kff.l(PG:132)
E/HttpOperation( 6554): 	at ieo.a(PG:43)
E/HttpOperation( 6554): 	at iep.a(PG:93)
E/HttpOperation( 6554): 	at fhn.a(PG:59)
E/HttpOperation( 6554): 	at lex.a(PG:85)
E/HttpOperation( 6554): 	at lex.b(PG:132)
E/HttpOperation( 6554): 	at fhk.a(PG:1146)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 12 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 14 more
,E/ExperimentLoader( 6554): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6554): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6554): 	at kfv.a(PG:65)
E/ExperimentLoader( 6554): 	at kff.u(PG:385)
E/ExperimentLoader( 6554): 	at kfb.a(PG:29)
E/ExperimentLoader( 6554): 	at kff.l(PG:132)
E/ExperimentLoader( 6554): 	at ieo.a(PG:43)
E/ExperimentLoader( 6554): 	at iep.a(PG:93)
E/ExperimentLoader( 6554): 	at fhn.a(PG:59)
E/ExperimentLoader( 6554): 	at lex.a(PG:85)
E/ExperimentLoader( 6554): 	at lex.b(PG:132)
E/ExperimentLoader( 6554): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6554): 	at fhk.a(PG:908)
E/ExperimentLoader( 6554): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6554): 	at ihi.a(PG:22)
E/ExperimentLoader( 6554): 	at kft.a(PG:91)
E/ExperimentLoader( 6554): 	at kfv.a(PG:62)
E/ExperimentLoader( 6554): 	... 12 more
E/ExperimentLoader( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6554): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6554): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6554): 	at ihi.a(PG:19)
E/ExperimentLoader( 6554): 	... 14 more
E/SMD     (  286): DCD ON
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
D/SecContentProvider2(  823): mCursor = null
,D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6554): [getaccountstatus] Unexpected exception
E/HttpOperation( 6554): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6554): 	at kfv.a(PG:65)
E/HttpOperation( 6554): 	at kff.u(PG:385)
E/HttpOperation( 6554): 	at kfb.a(PG:29)
E/HttpOperation( 6554): 	at ixd.a(PG:248)
E/HttpOperation( 6554): 	at ixd.b(PG:206)
E/HttpOperation( 6554): 	at ixd.a(PG:175)
E/HttpOperation( 6554): 	at fig.a(PG:78)
E/HttpOperation( 6554): 	at lex.a(PG:85)
E/HttpOperation( 6554): 	at lex.b(PG:132)
E/HttpOperation( 6554): 	at fhk.a(PG:1146)
E/HttpOperation( 6554): 	at fhk.a(PG:908)
E/HttpOperation( 6554): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6554): 	at ihi.a(PG:22)
E/HttpOperation( 6554): 	at kft.a(PG:91)
E/HttpOperation( 6554): 	at kfv.a(PG:62)
E/HttpOperation( 6554): 	... 12 more
E/HttpOperation( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6554): 	at gde.c(Unknown Source)
E/HttpOperation( 6554): 	at gde.b(Unknown Source)
E/HttpOperation( 6554): 	at ihi.a(PG:19)
E/HttpOperation( 6554): 	... 14 more
,E/EsSyncAdapterService( 6554): Sync failure
E/EsSyncAdapterService( 6554): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6554): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6554): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6554): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6554): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6554): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6554): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6554): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6554): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6554): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6554): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6554): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6554): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6554): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6554): 	... 10 more
E/EsSyncAdapterService( 6554): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6554): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6554): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6554): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6554): 	... 12 more
E/EsSyncAdapterService( 6554): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6554): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6554): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6554): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6554): 	... 14 more
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 213634, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  823): mCursor = null
,E/SQLiteLog( 1690): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/Watchdog(  823): !@Sync 7
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
,I/MotionRecognitionService(  823): setPowerConnected  = true
,D/BatteryService(  823): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/SSRM:m  (  823): SIOP:: AP = 310, PST = 319, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  823): Plugged
,I/MotionRecognitionService(  823): setPowerConnected  = true
,D/BatteryService(  823): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  823): SIOP:: AP = 300, PST = 315, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  823): waitForAlarm result :4
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7757): Starting books sync, d
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  823): SIOP:: AP = 300, PST = 312, CUR = 300
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7757): null auth token
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
,W/ApiaryClient( 7757): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2592427592172650234&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7757): null auth token
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
W/ApiaryClient( 7757): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2592427592172650234&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1690): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1690): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1690): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1690): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1690): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  823): uri = 14 selection = getSealedState
,D/SecContentProvider2(  823): mCursor = null
D/SecContentProvider2(  823): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  823): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  823): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1690): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1690): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1690): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1690): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1690): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7757): Authentication error
E/BooksAccountManager( 7757): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7757): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7757): null auth token
,I/qtaguid ( 7757): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7757, getuid(): 10082
,I/qtaguid ( 7757): Untagging socket 34
,W/ApiaryClient( 7757): Error response from books API: {
W/ApiaryClient( 7757):  "error": {
W/ApiaryClient( 7757):   "errors": [
W/ApiaryClient( 7757):    {
W/ApiaryClient( 7757):     "domain": "global",
W/ApiaryClient( 7757):     "reason": "required",
W/ApiaryClient( 7757):     "message": "Login Required",
W/ApiaryClient( 7757):     "locationType": "header",
W/ApiaryClient( 7757):     "location": "Authorization"
W/ApiaryClient( 7757):    }
W/ApiaryClient( 7757):   ],
W/ApiaryClient( 7757):   "code": 401,
W/ApiaryClient( 7757):   "message": "Login Required"
W/ApiaryClient( 7757):  }
W/ApiaryClient( 7757): }
,W/ApiaryClient( 7757): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2592427592172650234&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7757): Headers suppressed
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/BooksSync( 7757): Soft error
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2592427592172650234&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7757): Headers suppressed
E/BooksSync( 7757): 
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7757): Sync error
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7757): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2592427592172650234&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7757): Headers suppressed
E/BooksSync( 7757): 
E/BooksSync( 7757): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7757): Finished books sync
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 216685, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  823): mCursor = null
,D/ConnectivityService(  823): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  823): [PWL] Off : 180s ago
,E/Watchdog(  823): !@Sync 8
,E/SMD     (  286): DCD ON
,D/BatteryService(  823): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  823): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  823): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  823):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  823): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/MotionRecognitionService(  823): Plugged
,I/MotionRecognitionService(  823): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  823): SIOP:: AP = 300, PST = 309, CUR = 300
,V/HeadsetService( 3238): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3238): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,V/AlarmManager(  823): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  823): SIOP:: AP = 300, PST = 307, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/jxcore-log( 7228): --= Surplus to requirements =--
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ****TEST TOOK:  ms ****
I/jxcore-log( 7228): 
,I/jxcore-log( 7228): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7228): 
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 8385): 
D/AndroidRuntime( 8385): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8385): CheckJNI is OFF
,D/AndroidRuntime( 8385): setted country_code = Germany
D/AndroidRuntime( 8385): setted countryiso_code = DE
,D/AndroidRuntime( 8385): setted sales_code = DBT
,D/AndroidRuntime( 8385): readGMSProperty: start
D/AndroidRuntime( 8385): readGMSProperty: already setted!!
,D/AndroidRuntime( 8385): readGMSProperty: end
D/AndroidRuntime( 8385): addProductProperty: start
,E/AffinityControl( 8385): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8385): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  823): START PACKAGE DELETE: observer{488755154}
D/PackageManager(  823): pkg{<packageName>}
D/PackageManager(  823): user{0}
D/PackageManager(  823): caller{2000}
D/PackageManager(  823): flags{3}
D/PersonaManagerService(  823): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  823): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  823): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  823): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  823): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  823): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  823): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  823): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  823): getApplicationUninstallationEnabled
D/ApplicationPolicy(  823): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  823): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  823): Killing 7228:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  823):   Force finishing activity ActivityRecord{2e2ad87 u0 com.test.thalitest/.MainActivity t17}
,D/FocusedStackFrame(  823): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
,I/SurfaceFlinger(  249): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WifiService(  823): Client connection lost with reason: 4
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ConnectivityService(  823): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1590): Explicit concurrent mark sweep GC freed 11938(688KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 415us total 21.882ms
,I/art     ( 4577): Explicit concurrent mark sweep GC freed 4928(273KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 345us total 19.966ms
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010,
,E/SamsungIME( 1858): mOCRHelper is null
,W/GeofencerStateMachine( 2180): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7480): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7480): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1455035952250
,I/KLMS-2.4.503: ( 7480): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7480): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,I/art     (  823): Explicit concurrent mark sweep GC freed 40461(2MB) AllocSpace objects, 34(934KB) LOS objects, 30% free, 36MB/52MB, paused 3.600ms total 175.913ms
,I/art     (  823): WaitForGcToComplete blocked for 155.345ms for cause Explicit
,D/ResourcesManager(  823): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 2839): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/SecContentProvider2(  823): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  823): mCursor = null
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/RegisteredServicesCache( 1470): empty dynamic service
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  ( 8415): MountEmulatedStorage()
E/Zygote  ( 8415): v2
I/libpersona( 8415): KNOX_SDCARD checking this for 10104
I/libpersona( 8415): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8415 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,I/SELinux ( 8415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/EnterpriseDeviceManagerService(  823): Package has changed for user 0
D/EnterpriseDeviceManagerService(  823): Admin package name: com.google.android.gms
,D/TimaKeyStoreProvider( 8415): TimaSignature is unavailable
,D/ActivityThread( 8415): Added TimaKeyStore provider
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 8415): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/RCPManagerService(  823): PackageReceiver onReceive()
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/HarmonyEASService(  823): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/SurfaceWidgetView( 1482): destroyHardwareResources():749311667
,V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  823): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  823): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/Launcher( 1482): onRestart, Launcher: 398472440
,D/Launcher( 1482): onStart, Launcher: 398472440
D/Launcher.HomeView( 1482): onStart
,D/KnoxMUMContainerPolicy(  823): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2282): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2282): [237392/6] SurfaceWidget drawing first frame
,D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
,I/SurfaceFlinger(  249): id=16 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,V/EnterpriseBillingPolicy(  823): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  823): uID is 10200
V/EnterpriseBillingPolicy(  823): Removed Packageuid is0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/StatusBarManagerService(  823): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/EnterpriseBillingPolicyStorage(  823): getProfileForApplication - enter
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/EnterpriseBillingPolicyStorage(  823): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  823): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  823): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  823): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  823): getBillingProfileForVpnEngine - end - null
,D/StatusBarManagerService(  823): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/TaskPersister(  823): removeObsoleteFile: deleting file=17_task.xml
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/art     (  823): Suspending all threads took: 5.186ms
,D/InputMethodManagerService(  823): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl(  823): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 7228 uid 10200
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/elm:14451( 8415): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8415): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8415): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8415): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/elm:14451( 8415): ElmAgentService : onCreate()
,D/elm:14451( 8415): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8415): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 8415): MDMBridge.getInstance()
D/elm:14451( 8415): MDMBridge.getAllLicenseInfoFromSDK()
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7935): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 7935): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7935): onReceive() : package name is not s health. Return !!!
,D/elm:14451( 8415): MDMBridge.getAllLicenseInfoFromSDK()
,I/art     (  823): Explicit concurrent mark sweep GC freed 12966(697KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 12.596ms total 304.755ms
,D/elm:14451( 8415): ElmAgentService : onDestroy().
,I/PCWCLIENTTRACE_PushUtil( 6711): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6711): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6711): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6711): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/Timeline(  823): Timeline: Activity_windows_visible id: ActivityRecord{38fd93b4 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:270970
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/Zygote  ( 8437): MountEmulatedStorage()
I/libpersona( 8437): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8437): v2
I/libpersona( 8437): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8437 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/PackageManager(  823): delete codoeFile: 
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/PackageManager(  823): result of delete: 1{488755154}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  823): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  823): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  823): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/SELinux ( 8437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  823): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,I/SELinux ( 8437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8437): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  823): Killing 6633:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,D/AndroidRuntime( 8385): Shutting down VM
,D/ResourcesManager(  823): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/TimaKeyStoreProvider( 8437): TimaSignature is unavailable
,D/ActivityThread( 8437): Added TimaKeyStore provider
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/libprocessgroup(  823): failed to open /acct/uid_10012/pid_6633/cgroup.procs: No such file or directory
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 8437): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  823): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  823): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  823): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  823): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/SPPClientService( 8437): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8437): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/SPPClientService( 8437): PushLog.txt file is not deleted.
D/SPPClientService( 8437): PushLog.txt file is not deleted.
D/SPPClientService( 8437): ============PushLog. stop!
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SA      ( 6749): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SA      ( 6749): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ResourcesManager( 7860): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ActivityManager(  823): Killing 7043:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,W/ResourcesManager( 7860): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  823): failed to open /acct/uid_10170/pid_7043/cgroup.procs: No such file or directory
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7860): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7860): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7860): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7860): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 8456): MountEmulatedStorage()
E/Zygote  ( 8456): v2
I/libpersona( 8456): KNOX_SDCARD checking this for 10050
I/libpersona( 8456): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8456 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  823): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 8456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8456): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 8468): MountEmulatedStorage()
E/Zygote  ( 8468): v2
I/libpersona( 8468): KNOX_SDCARD checking this for 10020
I/libpersona( 8468): KNOX_SDCARD not a persona
,I/ActivityManager(  823): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=8468 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 828us total 31.639ms
,D/TimaKeyStoreProvider( 8456): TimaSignature is unavailable
,D/ActivityThread( 8456): Added TimaKeyStore provider
I/SELinux ( 8468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8468): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 695us total 27.638ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 689us total 21.353ms
,D/ResourcesManager( 8456): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8456): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8456): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8456): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8456): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8456): Unable to create files subdir /data/data/com.android.mms/cache
,E/ActivityThread( 8456): Unable to setupGraphicsSupport due to missing cache directory
,D/TimaKeyStoreProvider( 8468): TimaSignature is unavailable
,D/ActivityThread( 8468): Added TimaKeyStore provider
,I/EventHub(  823): Removing device '/dev/input/event4' due to inotify event
,D/ResourcesManager( 8468): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/AndroidRuntime( 8456): Shutting down VM
,W/ContextImpl( 8468): Unable to create files subdir /data/user/0/com.sec.android.provider.logsprovider/cache
,E/ActivityThread( 8468): Unable to setupGraphicsSupport due to missing cache directory
,E/AndroidRuntime( 8456): FATAL EXCEPTION: main
E/AndroidRuntime( 8456): Process: com.android.mms, PID: 8456
E/AndroidRuntime( 8456): java.lang.RuntimeException: Unable to instantiate application com.android.mms.MmsApp: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8456): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 8456): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8456): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8456): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8456): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8456): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8456): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8456): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8456): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8456): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8456): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8456): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8456): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8456): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8456): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 8456): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 8456): 	... 10 more
E/AndroidRuntime( 8456): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/SecMms_Candy/SecMms_Candy.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8456): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8456): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8456): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8456): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8456): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8456): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8456): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8456): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8456): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8456): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8456): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8456): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8456): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8456): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8456): 		at, android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8456): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8456): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8456): 		... 10 more
E/AndroidRuntime( 8456): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SecMms_Candy/SecMms_Candy.apk'
E/AndroidRuntime( 8456): 		... 27 more
E/AndroidRuntime( 8456): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SecMms_Candy/arm/SecMms_Candy.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8456): 		... 27 more
E/AndroidRuntime( 8456): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8456): 		... 27 more
E/AndroidRuntime( 8456): 	Suppressed: java.lang.ClassNotFoundException: com.android.mms.MmsApp
E/AndroidRuntime( 8456): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8456): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8456): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8456): 		at java.lang.ClassLoade
F/libc    ( 8456): Fatal signal 7 (SIGBUS), code 2, fault addr 0x76b43198 in tid 8456 (com.android.mms)
I/EventHub(  823): Removing device '/dev/input/event5' due to inotify event
E/audit_log( 2095): File locking failed. error= Bad file number
D/AndroidRuntime( 8468): Shutting down VM
F/libc    ( 8456): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2095): File locking failed. error= Bad file number
E/AndroidRuntime( 8468): FATAL EXCEPTION: main
E/AndroidRuntime( 8468): Process: com.sec.android.provider.logsprovider, PID: 8468
E/AndroidRuntime( 8468): java.lang.RuntimeException: Unable to get provider com.sec.android.provider.logsprovider.LogsProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.provider.logsprovider.LogsProvider" on path: DexPathList[[zip file "/system/priv-app/LogsProvider/LogsProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8468): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8468): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8468): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8468): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8468): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8468): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8468): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8468): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8468): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8468): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8468): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8468): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8468): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.provider.logsprovider.LogsProvider" on path: DexPathList[[zip file "/system/priv-app/LogsProvider/LogsProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8468): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8468): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8468): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8468): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5441)
E/AndroidRuntime( 8468): 	... 11 more
E/AndroidRuntime( 8468): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/LogsProvider/LogsProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8468): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8468): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8468): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8468): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8468): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8468): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8468): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8468): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8468): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8468): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8468): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8468): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8468): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8468): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8468): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8468): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8468): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8468): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4980)
E/AndroidRuntime( 8468): 		... 9 more
E/AndroidRuntime( 8468): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/LogsProvider/LogsProvider.apk'
E/AndroidRuntime( 8468): 		... 27 more
E/AndroidRuntime( 8468): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/LogsProvider/arm/LogsProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8468): 		... 27 more
E/AndroidRuntime( 8468): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8468): 		... 27 more
E/AndroidRuntime( 8468): 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.provider.logsprovider.LogsProvider
E/AndroidRuntime( 8468): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8468): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8468): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8468): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8468): 		... 13 more
E/AndroidRuntime( 8468): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
F/libc    ( 8468): Fatal signal 7 (SIGBUS), code 2, fault addr 0x76b43198 in tid 8468 (er.logsprovider)
F/libc    ( 8468): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2095): File locking failed. error= Bad file number
E/SMD     (  286): DCD ON
,I/ActivityManager(  823): Process com.android.mms (pid 8456)(adj 0) has died(177,531)
I/ActivityManager(  823): Process com.sec.android.provider.logsprovider (pid 8468)(adj 5) has died(177,531)
F/libc    (  823): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0909eeb in tid 1528 (Binder_7)
F/libc    (  823): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2095): File locking failed. error= Bad file number
,I/Zygote  (  313): Process 8456 exited due to signal (7)
,I/Zygote  (  313): Process 8468 exited due to signal (7)
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/installd(  295): eof
E/installd(  295): failed to read size
I/installd(  295): closing connection
,W/Sensors ( 7980): sensorservice died [0xaf0f9580]
,W/AudioFlinger(  292): power manager service died !!!
W/AudioFlinger(  292): power manager service died !!!
,D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
,F/libc    ( 1786): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b65bd in tid 8453 (IntentService[V)
F/libc    ( 1786): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
,I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (5/8)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/7)
,I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'textservices' died
W/Sensors ( 2180): sensorservice died [0xaf0ef0c0]
I/ServiceManager(  247): service 'network_score' died
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'backup' died
E/WifiManager( 2180): Channel connection lost
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
I/ServiceManager(  247): service 'commontime_management' died
I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'wifi' died
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died
I/ServiceManager(  247): service 'country_detector' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/Se,rviceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
W/Sensors ( 1170): sensorservice died [0xaf0d00c0]
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
E/WifiManager( 1170): Channel connection lost
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (0/4)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/4)
,I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=16 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (1/3)
,W/Sensors ( 1464): sensorservice died [0xaf099b80]
,W/Sensors ( 1298): sensorservice died [0x9d6212c0]
,I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (0/2)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/2)
,I/SurfaceFlinger(  249): id=16 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/2)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (0/1)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/1)
I/SurfaceFlinger(  249): id=13 Removed ColorFade (0/0)
W/Sensors ( 1476): sensorservice died [0xaf0d4340]
I/SurfaceFlinger(  249): id=13 Removed ColorFade (-2/0)
E/WifiManager( 1298): Channel connection lost
,E/WifiManager( 1710): Channel connection lost
E/WifiManager( 1590): Channel connection lost
,E/WifiManager( 1476): Channel connection lost
,W/Sensors ( 1482): sensorservice died [0xaf09e380]
,I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
W/Sensors ( 2219): sensorservice died [0xaf099c40]
,I/Zygote  (  313): Process 1786 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,F/libc    (  249): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb6b06268 in tid 249 (surfaceflinger)
F/libc    (  249): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/ServiceManager(  247): service 'SurfaceFlinger' died
I/ServiceManager(  247): service 'display.qservice' died
,W/SurfaceComposerClient( 1482): ComposerService remote (surfaceflinger) died [0xaf09e1c0]
,W/SurfaceComposerClient( 1170): ComposerService remote (surfaceflinger) died [0xaf0d0380]
,W/SurfaceComposerClient( 1710): ComposerService remote (surfaceflinger) died [0xaf0a3400]
,W/SurfaceComposerClient( 2282): ComposerService remote (surfaceflinger) died [0xaf067b00]
,W/SurfaceComposerClient( 5823): ComposerService remote (surfaceflinger) died [0xaf0ff700]
,E/DisplayEventReceiver( 1170): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/OpenGLRenderer( 1482): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 5823): Display event receiver pipe was closed or an error occurred.  events=0x9
E/OpenGLRenderer( 1170): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 2282): Display event receiver pipe was closed or an error occurred.  events=0x9
E/DisplayEventReceiver( 1710): Display event receiver pipe was closed or an error occurred.  events=0x9
,E/DisplayEventReceiver( 1482): Display event receiver pipe was closed or an error occurred.  events=0x9

```
