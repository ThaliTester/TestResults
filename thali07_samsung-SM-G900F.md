#### Test 54970261aa56788_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
I/qtaguid ( 7356): Untagging socket 34
W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035881567439869054&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
--------- beginning of system
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7411): 
D/AndroidRuntime( 7411): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7411): CheckJNI is OFF
D/AndroidRuntime( 7411): setted country_code = Germany
D/AndroidRuntime( 7411): setted countryiso_code = DE
D/AndroidRuntime( 7411): setted sales_code = DBT
D/AndroidRuntime( 7411): readGMSProperty: start
D/AndroidRuntime( 7411): readGMSProperty: already setted!!
D/AndroidRuntime( 7411): readGMSProperty: end
D/AndroidRuntime( 7411): addProductProperty: start
E/AffinityControl( 7411): AffinityControl: registerfunction enter
D/AndroidRuntime( 7411): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  846): inState():  stateMachine is null !!
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  846): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  846): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  846): mDVFSHelper.acquire()
D/FocusedStackFrame(  846): Set to : 0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  846): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7428 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7428): MountEmulatedStorage()
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Zygote  ( 7428): v2
I/libpersona( 7428): KNOX_SDCARD checking this for 10367
I/libpersona( 7428): KNOX_SDCARD not a persona
D/AndroidRuntime( 7411): Shutting down VM
I/SELinux ( 7428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7428): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 7428): TimaSignature is unavailable
D/ActivityThread( 7428): Added TimaKeyStore provider
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  846): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  846): Display changed displayId=0
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
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetView( 1478): destroyHardwareResources():11941581
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
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
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2140): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 7428): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SQLiteSecureOpenHelper( 3578): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3578): getDatabaseLocked(b,b,pwd)...
D/Launcher( 1478): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/WebViewFactory( 7428): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7428): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7428): Loading: webviewchromium
I/LibraryLoader( 7428): Time to load native libraries: 2 ms (timestamps 6143-6145)
I/LibraryLoader( 7428): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7428): Binding Chromium to main looper Looper (main, tid 1) {13a7b821}
I/LibraryLoader( 7428): Expected native library version number "",actual native library version number ""
I/chromium( 7428): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7428): Initializing chromium process, renderers=0
W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7428): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7428): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7428): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7428): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7428): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7428): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7428): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7428): Remote Branch: 
I/Adreno-EGL( 7428): Local Patches: 
I/Adreno-EGL( 7428): Reconstruct Branch: 
W/chromium( 7428): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7428): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7428): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7428): CordovaWebView is running on device made by: samsung
E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035881567439869054&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8035881567439869054&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7356): Finished books sync
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7428): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  846): Killing 6033:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63635, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  846): failed to open /acct/uid_10044/pid_6033/cgroup.procs: No such file or directory
D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
D/Activity( 7428): performCreate Call secproduct feature valuefalse
D/Activity( 7428): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7428): Render dirty regions requested: true
D/ActivityManager(  846): post active user change for 0
D/KnoxTimeoutHandler(  846): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  846): handleActiveUserChange for user 0
I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/StatusBarManagerService(  846): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  846): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/OpenGLRenderer( 7428): Initialized EGL, version 1.4
I/OpenGLRenderer( 7428): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7428): Enabling debug mode 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/InputMethodManagerService(  846): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ActivityManager(  846): mDVFSHelper.release()
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{3f34c79a u0 com.test.thalitest/.MainActivity t11} time:96627
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/IInputConnectionWrapper( 7428): showStatusIcon on inactive InputConnection
W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 7428): Timeline: Activity_idle id: android.os.BinderProxy@354cb1b8 time:96635
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/JsMessageQueue( 7428): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7428): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259382784
D/JX-Cordova( 7428): jxcore cordova android initializing
,I/GAV2    ( 7356): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  282): DCD ON
,W/jxcore-log( 7428): Initializing JXcore engine
W/jxcore-log( 7428): JXcore engine is ready
,W/jxcore-log( 7428): Starting JXcore engine
,E/auditd  ( 2142): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  846): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  846): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7499): MountEmulatedStorage()
E/Zygote  ( 7499): v2
I/libpersona( 7499): KNOX_SDCARD checking this for 1000
I/libpersona( 7499): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7499 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7499): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7499): TimaSignature is unavailable
,W/jxcore-log( 7428): Platform android
W/jxcore-log( 7428): 
W/jxcore-log( 7428): Process ARCH arm
W/jxcore-log( 7428): 
D/ActivityThread( 7499): Added TimaKeyStore provider
,D/ResourcesManager( 7499): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7499):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7499):  SeDenialReceiver : File path = null
,I/ActivityManager(  846): Killing 5365:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,W/libprocessgroup(  846): failed to open /acct/uid_10126/pid_5365/cgroup.procs: No such file or directory
,I/jxcore-log( 7428): JXcore Cordova bridge is ready!
I/jxcore-log( 7428): 
,W/jxcore-log( 7428): JXcore engine is started
,I/jxcore-log( 7428): Toggling radios to true
I/jxcore-log( 7428): 
,D/BluetoothAdapter( 7428): enable()
,D/BluetoothAdapter( 7428): enable(): BT is already enabled..!
,D/WifiService(  846): New client listening to asynchronous messages
,I/WifiManager( 7428): packageName : com.test.thalitest
,D/SecContentProvider(  846): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  846): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  846): mCursor = null
,D/WifiService(  846): setWifiEnabled: true pid=7428, uid=10367
,E/WifiService(  846): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  846): Permission Denial: getCurrentUser() from pid=7428, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  846): Failed getting userId using ActivityManagerNative
W/WifiService(  846): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7428, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  846): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  846): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  846): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  846): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  846): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  846): name = wifi_on
,I/WifiService(  846): disconnect: pid=7428, uid=10367
,I/jxcore-log( 7428): Radios toggled
I/jxcore-log( 7428): 
,I/wpa_supplicant( 1288): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1288): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1288): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1288): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  846): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1288): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1288): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1288): Disconnected - do not scan
I/wpa_supplicant( 1288): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  846): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  846): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  846): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  846): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  846): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  846): do suspend true
,D/WifiP2pService(  846): InactiveState{ what=143375 }
,D/WifiP2pService(  846): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  846): waitForAlarm result :4
,D/CommandListener(  276): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1692): Read error: ssl=0xafb27e00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  846): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  846): updateNetworkInfo()
,D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  846): updateNetworkInfo()
,D/ConnectivityService(  846): ignoring duplicate network state non-change
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  846): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1288): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1288): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1288): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1288): First Scan Start
,I/wpa_supplicant( 1288): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  846): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  846): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,I/WifiTrafficPoller(  846): evaluateTrafficStatsPolling
,I/CLocInfoService(  846): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,V/NativeCrypto( 1692): SSL shutdown failed: ssl=0xafb27e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  846): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  846): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  846): do suspend true
,D/WifiP2pService(  846): InactiveState{ what=143375 }
,D/WifiP2pService(  846): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1302): Starting #6
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/Hs20UtilService( 1302): Message received 5007
D/CommandListener(  276): Clearing all IP addresses on wlan0
,D/ConnectivityService(  846): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  846): calling update connectivity
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  846): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  846): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  846): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  846): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/EntConnectivity(  846): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  846): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/TelephonyNetworkFactory( 1470): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  846): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  846): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  846): Disconnected - quitting
,D/CSLegacyTypeTracker(  846): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  846): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiStateMachine(  846): updateConfiguredNetworkExpiration - currTime: 1452019240085
,D/WifiStateMachine(  846): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/SmartBondingService(  846): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  846): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
,E/WifiStateMachine(  846): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  846): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,V/NetworkStats(  846): updateIfacesLocked()
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
V/NetworkStats(  846): performPollLocked(flags=0x1)
D/WifiNetworkAgent(  846): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  846): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
E/WifiStateMachine(  846): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  846): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  846): setDetailed state send new extra info"NG700"
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/NetworkStatsFactory(  846): UpdateStatsForKnox
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,I/WifiTrafficPoller(  846): evaluateTrafficStatsPolling
,D/SecContentProvider2(  846): uri = 20 selection = getPromptCredentialsEnabled
I/CLocInfoService(  846): External Intent Received android.net.wifi.STATE_CHANGE
D/SecContentProvider2(  846): mCursor = null
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
V/NetworkStats(  846): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
D/SecContentProvider2(  846): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  846): mCursor = null
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NetworkStats(  846): performPollLocked() took 19ms
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,I/Hs20UtilService( 1302): Starting #7
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1470): FileWriteThread : threadType = 3
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 2.
,D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  846): updateDataUsageMap
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  846): MasterInitialState.processMessage what=3
D/SmartBondingService(  846): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  846): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
,D/SmartBondingService(  846): getNetworkEnabled : wifi : true mobile : true
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  846): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  846): CLoinfo wifi false
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6808): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6808): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6808): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6808): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6808): noConnectivity : true
,I/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,W/SLocation(  846): No Active Data Connection
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7558): MountEmulatedStorage()
I/libpersona( 7558): KNOX_SDCARD checking this for 10126
E/Zygote  ( 7558): v2
I/libpersona( 7558): KNOX_SDCARD not a persona
I/ActivityManager(  846): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=7558 uid=10126 gids={50126, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7558): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7558): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7558): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7558): TimaSignature is unavailable
,D/ActivityThread( 7558): Added TimaKeyStore provider
,D/ResourcesManager( 7558): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore( 7558): Database version: 104
,E/SMD     (  282): DCD ON
,D/ResourcesManager( 7558): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7558): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7558): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7558): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 7558): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7558): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@268bf363: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7558): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7558): GMSCore installation verified
,I/ConfigStore( 7558): Config Database version: 1
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7558): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7558): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7558): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter(  846): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 1288): nl80211: Received scan results (6 BSSes)
D/WifiDisplayAdapter(  846): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/wpa_supplicant( 1288): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1288): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1288): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  846): [1,452,019,241,098 ms] noteScanEnd no scan source
,V/AudioPolicyManager(  291): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  846): getStreamVolume 3 index 70
,I/MediaRouter( 7558): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/WifiStateMachine(  846): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@34f14571 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  846): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  846): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  846): setDetailed state send new extra info0x
,D/SecContentProvider2(  846): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  846): mCursor = null
I/CLocInfoService(  846): External Intent Received android.net.wifi.SCAN_RESULTS
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7593): MountEmulatedStorage()
E/Zygote  ( 7593): v2
I/libpersona( 7593): KNOX_SDCARD checking this for 10002
I/libpersona( 7593): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7593 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 13.323ms
,I/SELinux ( 7593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 8.688ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.151ms
,D/WifiDisplayAdapter(  846): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 7593): TimaSignature is unavailable
,D/ActivityThread( 7593): Added TimaKeyStore provider
,I/wpa_supplicant( 1288): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1288): Associated with C0.AA.48
,E/WifiStateMachine(  846): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  846): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  846): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  846): mCursor = null
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7558): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager(  846): Killing 6312:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,D/ResourcesManager( 7593): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/wpa_supplicant( 1288): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  846): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  846): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  846): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  846): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  846): mCursor = null
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 26444(1617KB) AllocSpace objects, 17(1377KB) LOS objects, 40% free, 17MB/29MB, paused 480us total 22.137ms
,I/ActivityManager(  846): Killing 6595:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1288): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,E/Zygote  ( 7612): MountEmulatedStorage()
,E/Zygote  ( 7612): v2
I/libpersona( 7612): KNOX_SDCARD checking this for 1000
I/libpersona( 7612): KNOX_SDCARD not a persona
,I/wpa_supplicant( 1288): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/ActivityManager(  846): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7612 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  846): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  846): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1288): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1288): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1288): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1288): Blacklist: Clear (temp) 
I/wpa_supplicant( 1288): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  846): Network connection established
,D/WifiNative-HAL(  846): callSECApiVoid - ID [50]
E/WifiStateMachine(  846): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  846): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  846): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  846): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  846): Got NetworkAgent Messenger
D/ConnectivityService(  846): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  846): updateNetworkInfo()
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846): NetworkAgent connected
,E/WifiStateMachine(  846): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  846): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SELinux ( 7612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  846): failed to open /acct/uid_10117/pid_6312/cgroup.procs: No such file or directory
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SELinux ( 7612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7612): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  846): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  846): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  846): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  846): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine(  846): Start Dhcp Watchdog 2
D/SecContentProvider2(  846): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  846): mCursor = null
,W/libprocessgroup(  846): failed to open /acct/uid_10075/pid_6595/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7612): TimaSignature is unavailable
,D/ActivityThread( 7612): Added TimaKeyStore provider
E/WifiStateMachine(  846): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  846): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ResourcesManager( 7612): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7612): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7612): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine(  846): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  846): do suspend false
,D/SecContentProvider2(  846): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  846): InactiveState{ what=143375 }
,D/WifiP2pService(  846): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  846): mCursor = null
,I/DIAGMON_AGENT( 7612): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7612): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7631): MountEmulatedStorage()
,E/Zygote  ( 7631): v2
I/libpersona( 7631): KNOX_SDCARD checking this for 10011
I/libpersona( 7631): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7631 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/dhcpcd  ( 7637): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7637): version 5.5.6 starting
,E/dhcpcd  ( 7637): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SELinux ( 7631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7631): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7631): TimaSignature is unavailable
,D/ActivityThread( 7631): Added TimaKeyStore provider
,I/dhcpcd  ( 7637): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7637): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7637): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7637): bssid match
,I/dhcpcd  ( 7637): wlan0: rebinding lease of 192.168.1.135
,D/ResourcesManager( 7631): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  846): Killing 6618:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7631): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7631): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7631): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7631): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7631): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7653): MountEmulatedStorage()
I/libpersona( 7653): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7653): v2
I/libpersona( 7653): KNOX_SDCARD not a persona
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6618/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7653 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6652:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/SELinux ( 7653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7653): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7653): TimaSignature is unavailable
,D/ActivityThread( 7653): Added TimaKeyStore provider
,D/ResourcesManager( 7653): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7653): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7653): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452019241834
,I/KLMS-2.4.503: ( 7653): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.503: ( 7653): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6652/cgroup.procs: No such file or directory
I/KLMS-2.4.503: ( 7653): StateImplV2(): networkChangeListener().END
I/ActivityManager(  846): Killing 6763:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7668): MountEmulatedStorage()
,E/Zygote  ( 7668): v2
I/libpersona( 7668): KNOX_SDCARD checking this for 10037
I/libpersona( 7668): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7668 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/dhcpcd  ( 7637): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/SELinux ( 7668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7668): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7668): TimaSignature is unavailable
,D/ActivityThread( 7668): Added TimaKeyStore provider
,I/dhcpcd  ( 7637): wlan0: leased 192.168.1.135 for 86400 seconds
,D/ResourcesManager( 7668): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/WifiStateMachine(  846): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  846): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SO_AGENT( 7668): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  846): failed to open /acct/uid_10015/pid_6763/cgroup.procs: No such file or directory
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5171): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6846): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6846): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6846): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6846): [SLFUCHKMGR] constructor called
,I/SA      ( 6846): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6846): [OR] == isSIMCardReady false ==
,I/SA      ( 6846): [SCU] == networkStateCheck == false
I/SA      ( 6846): [OR] onReceive END
,E/SPPClientService( 5171): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7695): MountEmulatedStorage()
E/Zygote  ( 7695): v2
I/libpersona( 7695): KNOX_SDCARD checking this for 10071
I/libpersona( 7695): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7695 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  846): Killing 6792:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7695): TimaSignature is unavailable
,D/ActivityThread( 7695): Added TimaKeyStore provider
,D/ResourcesManager( 7695): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7695): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7695): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7695): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7695): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7695): [KK AccuPhone]>>> ==============================================================================================
,W/libprocessgroup(  846): failed to open /acct/uid_10016/pid_6792/cgroup.procs: No such file or directory
,D/comsamsunglog( 7695): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7695): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7695): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7695): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  846): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  846): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  846): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  846): selectionArgs: false
D/SettingsProvider(  846): selectionArgs: 10071
D/SecContentProvider(  846): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  846): ret = -1
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7695): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7695): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7695): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7695): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7695): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7695): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7695): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7695): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1330): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7695): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7695): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7725): MountEmulatedStorage()
E/Zygote  ( 7725): v2
I/libpersona( 7725): KNOX_SDCARD checking this for 1000
I/libpersona( 7725): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7725 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6574:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/WifiStateMachine(  846): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  846): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  846): do suspend true
,D/WifiP2pService(  846): InactiveState{ what=143375 }
,D/WifiP2pService(  846): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  846): WifiStateMachine DHCP successful
,E/WifiStateMachine(  846): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  846): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  846): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  846): Not connected state, yet.
E/WifiStateMachine(  846): VerifyingLinkState enter
,I/SELinux ( 7725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SELinux ( 7725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/WifiStateMachine(  846): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  846): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  846): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  846): callSECApiInt - ID [210]
E/WifiStateMachine(  846): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  846): updateNetworkInfo()
E/SELinux ( 7725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  846): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  846): Adding iface wlan0 to network 503
,I/CLocInfoService(  846): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  846): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  846): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  846): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  846): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  846): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  846): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  846): Now, connected state.
E/WifiStateMachine(  846): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  846): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  846): evaluateTrafficStatsPolling
,I/CLocInfoService(  846): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  846): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  846): mBoosterFLAG : 0
I/WifiTrafficPoller(  846): current booster mode : FullMode
D/WifiNative-HAL(  846): callSECApiVoid - ID [212]
,I/CLocInfoService(  846): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService(  846): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/ConnectivityService(  846): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine(  846): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/TimaKeyStoreProvider( 7725): TimaSignature is unavailable
D/ConnectivityService(  846): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/ActivityThread( 7725): Added TimaKeyStore provider
E/ConnectivityService(  846): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  846): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  846): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  276): QcRouteController
W/libprocessgroup(  846): failed to open /acct/uid_10034/pid_6574/cgroup.procs: No such file or directory
,E/WifiStateMachine(  846): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine(  846): REQUEST_POWER_SAVE_ON
,D/ResourcesManager( 7725): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7725): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/        (  276): QcRouteController
,I/KnoxUsageLogPro( 7725): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7725): premStatus:2
,V/        (  276): QcRouteController
,I/KnoxUsageLogPro( 7725): isEulaShown : false
,I/KnoxUsageLogPro( 7725): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,V/        (  276): QcRouteController
,E/Zygote  ( 7751): MountEmulatedStorage()
,E/Zygote  ( 7751): v2
I/libpersona( 7751): KNOX_SDCARD checking this for 10088
I/libpersona( 7751): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7751 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 4617:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,I/SELinux ( 7751): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7751): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7751): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  846): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  846): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  846): updateNetworkInfo()
D/ConnectivityService(  846): calling update connectivity
E/ConnectivityService(  846): updateNetworkInfo()
D/ConnectivityService(  846): ignoring duplicate network state non-change
D/ConnectivityService(  846): ignoring duplicate network state non-change
D/ConnectivityService(  846): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  846): calling update connectivity
D/ConnectivityService(  846): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  846):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846): currentScore = 0, newScore = 60
D/ConnectivityService(  846):    accepting network in place of null
D/ConnectivityService(  846): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  846): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  846): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  846): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  846): Validated
,D/TelephonyNetworkFactory( 1470): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  846): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  846): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ActivityManager(  846): Failed to clear dns cache for: com.sec.android.app.shealth
,D/ConnectivityService(  846): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  846): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/TimaKeyStoreProvider( 7751): TimaSignature is unavailable
,D/ConnectivityService(  846): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  846): calling update connectivity
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ActivityThread( 7751): Added TimaKeyStore provider
D/ConnectivityService(  846): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  846): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  846):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  846):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  846): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  846): calling update connectivity
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/SmartBondingService(  846): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  846): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
,V/NetworkStats(  846): updateIfacesLocked()
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
D/SmartBondingService(  846): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  846): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  846): UpdateStatsForKnox
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,V/NetworkStats(  846): performPollLocked() took 3ms
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
V/NetworkStats(  846): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7751): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  846): failed to open /acct/uid_10035/pid_4617/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Killing 6095:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,D/Headlines( 5526): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5526): getCountryCode(): countryCode = DE
,D/Headlines( 5526): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5526): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5526): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5526): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5526): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5526): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5526): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7773): MountEmulatedStorage()
E/Zygote  ( 7773): v2
I/libpersona( 7773): KNOX_SDCARD checking this for 10128
I/libpersona( 7773): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7773 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7773): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7773): TimaSignature is unavailable
,D/ActivityThread( 7773): Added TimaKeyStore provider
,D/ResourcesManager( 7773): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  846): failed to open /acct/uid_10042/pid_6095/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7773): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7773): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7773): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7773): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7773): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ConnectivityService(  846): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ResourcesManager( 7773): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  846): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  846): MasterInitialState.processMessage what=3
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  846): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  846): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  846): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  846): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  846): getSBEnabled() enabled =false
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  846): CLocinfo wifi true 
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  846): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2197): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3818): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7558): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/LibraryLoader( 7773): Loading: webviewchromium
,I/LibraryLoader( 7773): Time to load native libraries: 6 ms (timestamps 2503-2509)
,I/LibraryLoader( 7773): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7773): Binding Chromium to main looper Looper (main, tid 1) {2f3f871d}
,I/LibraryLoader( 7773): Expected native library version number "",actual native library version number ""
,I/chromium( 7773): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7773): Initializing chromium process, renderers=0
,W/art     ( 7773): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7773): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7773): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7773): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7773): Requires BLUETOOTH permission
,I/Adreno-EGL( 7773): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7773): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7773): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7773): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7773): Remote Branch: 
I/Adreno-EGL( 7773): Local Patches: 
I/Adreno-EGL( 7773): Reconstruct Branch: 
,I/art     (  846): Explicit concurrent mark sweep GC freed 67350(3MB) AllocSpace objects, 8(258KB) LOS objects, 30% free, 36MB/52MB, paused 1.389ms total 86.563ms
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
,I/NSApplication( 7773): Starting up...
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7837): MountEmulatedStorage()
E/Zygote  ( 7837): v2
I/libpersona( 7837): KNOX_SDCARD checking this for 10138
I/libpersona( 7837): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7837 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 6052:com.sec.android.gallery3d/u0a48 (adj 15): bgCount ##41
,I/SELinux ( 7837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7837): TimaSignature is unavailable
,D/ActivityThread( 7837): Added TimaKeyStore provider
,W/libprocessgroup(  846): failed to open /acct/uid_10048/pid_6052/cgroup.procs: No such file or directory
,D/ResourcesManager( 7837): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7837): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7837): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7837): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7837): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7853): MountEmulatedStorage()
E/Zygote  ( 7853): v2
I/libpersona( 7853): KNOX_SDCARD checking this for 10163
I/libpersona( 7853): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7853 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  846): Killing 5726:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CountryDetector(  846): No listener is left
,I/SELinux ( 7853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7853): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7853): TimaSignature is unavailable
,D/ActivityThread( 7853): Added TimaKeyStore provider
,D/ResourcesManager( 7853): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7853): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7853): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7853): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  846): failed to open /acct/uid_10050/pid_5726/cgroup.procs: No such file or directory
,D/ConnectivityService(  846): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/RCPManagerService(  846): exchangeData() failure , invalid userId
,D/RCPManagerService(  846): exchangeData() failure , invalid userId
,D/RCPManagerService(  846): exchangeData() failure , invalid userId
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  846): exchangeData() failure , invalid userId
,E/Zygote  ( 7875): MountEmulatedStorage()
,E/Zygote  ( 7875): v2
I/libpersona( 7875): KNOX_SDCARD checking this for 10078
I/libpersona( 7875): KNOX_SDCARD not a persona
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  846): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7875 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 288us total 10.880ms
,I/SELinux ( 7875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7875): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 8.001ms
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 8.450ms
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
D/RCPManagerService(  846): exchangeData() failure , invalid userId
,D/RCPManagerService(  846): exchangeData() failure , invalid userId
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,D/TimaKeyStoreProvider( 7875): TimaSignature is unavailable
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,D/ActivityThread( 7875): Added TimaKeyStore provider
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7499): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7499): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7499): StateMachine : Current State = 1
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  846): Killing 6872:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
D/SecurityLogAgent( 7499): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
I/ActivityManager(  846): Killing 6888:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/ResourcesManager( 7875): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/com.peel.receiver.ConnectivityActionReceiver( 5632): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): last run: 1451989033275 -- System.currentTimeMillis()-last_run: 30210259
D/com.peel.receiver.ConnectivityActionReceiver( 5632): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): ... skip last_72_check
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7875): onCreate
,D/BadgeProvider( 7875): DatabaseHelper
,E/Zygote  ( 7893): MountEmulatedStorage()
E/Zygote  ( 7893): v2
I/libpersona( 7893): KNOX_SDCARD checking this for 10178
I/libpersona( 7893): KNOX_SDCARD not a persona
,I/ActivityManager(  846): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7893 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7853): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 7893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7893): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7875): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7875): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7875): sendNotify, [notify] : null
D/BadgeProvider( 7875): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7875): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7875): update, [UpdateCount] : 1
,D/Launcher.Model( 1478): reloadBadges entered.
,D/TimaKeyStoreProvider( 7893): TimaSignature is unavailable
,D/ActivityThread( 7893): Added TimaKeyStore provider
,D/ResourcesManager( 7893): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/libprocessgroup(  846): failed to open /acct/uid_10058/pid_6888/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10051/pid_6872/cgroup.procs: No such file or directory
,I/ActivityManager(  846): Killing 6244:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2476): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager(  846): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2476): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7171): notifyNetworkActivated
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6244/cgroup.procs: No such file or directory
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/ContextImpl( 7171): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  846): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2476): [AccountUtils] Account not ready
W/Kids    ( 2476): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2476): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2476): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2476): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2476): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2476): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2476): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2476): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,D/hcjo    ( 7171): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7171): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7171): exit::IDLE
D/InitializeManagerStateMachine( 7171): entry::NETWORK_CHECK
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7171): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7171): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7171): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7171): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7171): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7171): entry::SUCCESS
D/hcjo    ( 7171): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1302): Starting #8
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/hcjo    ( 7171): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7171): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
D/InitializeManagerStateMachine( 7171): exit::SUCCESS
D/InitializeManagerStateMachine( 7171): entry::IDLE
,I/Hs20UtilService( 1302): Starting #9
,I/Hs20UtilService( 1302): Message received 5007
E/SMD     (  282): DCD ON
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1302): Starting #10
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1302): Starting #11
I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  846): callSECApi what=220
D/WifiStateMachine(  846): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6808): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6808): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6808): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6808): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=4, Toast
,I/DIAGMON_AGENT( 7612): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  846): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=846
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/FOTA_Client( 7631): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7631): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/FOTA_Client( 7631): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7631): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7631): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7653): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7653): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452019244048
,I/KLMS-2.4.503: ( 7653): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7653): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7653): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7653): NetworkChangeOperations(): uploadRequestLog().START 
,V/AlarmManager(  846): waitForAlarm result :4
,I/KLMS-2.4.503: ( 7653): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7668): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,E/Watchdog(  846): !@Sync 3
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4300, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5171): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6846): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6846): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6846): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6846): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6846): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6846): [SCU] == networkStateCheck == true
I/SA      ( 6846): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6846): isChinaCountryCode : false
I/SA      ( 6846): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6846): [OR] == networkStateCheck true ==
,I/PowerManagerService(  846): [PWL] Off : 30s ago
I/PowerManagerService(  846): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  846): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  846): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=846, ws=WorkSource{10012}) (elapsedTime=128)
,I/SA      ( 6846): [OR] GetMyCountryZoneTask
,I/SA      ( 6846): [OR] onReceive END
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6846): [SRS] prepareGetMyCountryZone
,I/SA      ( 6846): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6846): [SSP] query invoked
,D/accuweather( 7695): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7695): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6846): [TPMU] GetMccFromDB : null
,I/SA      ( 6846): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6846): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7725): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7725): premStatus:2
,I/KnoxUsageLogPro( 7725): isEulaShown : false
I/KnoxUsageLogPro( 7725): KnoxUsageReceiver onReceive : not Processible, just return
,D/Headlines( 5526): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5526): getCountryCode(): countryCode = DE
,D/Headlines( 5526): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5526): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5526): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5526): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5526): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5526): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5526): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 6846): fail readDirectory() errno=2
,D/SSRM:m  (  846): SIOP:: AP = 400, PST = 419, CUR = 300
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7837): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7837): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7837): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  846): exchangeData() failure , invalid userId
,D/RCPManagerService(  846): exchangeData() failure , invalid userId
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7499): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7499): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 7499): StateMachine : Current State = 1
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7499): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5632): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): last run: 1451989033275 -- System.currentTimeMillis()-last_run: 30211002
D/com.peel.receiver.ConnectivityActionReceiver( 5632): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5632): ... skip last_72_check
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2476): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2476): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7171): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7171): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7171): exit::IDLE
D/InitializeManagerStateMachine( 7171): entry::NETWORK_CHECK
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7171): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7171): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 7171): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7171): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7171): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7171): entry::SUCCESS
D/hcjo    ( 7171): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7171): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7171): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7171): exit::SUCCESS
D/InitializeManagerStateMachine( 7171): entry::IDLE
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2476): [AccountUtils] Account not ready
W/Kids    ( 2476): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2476): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2476): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2476): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2476): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2476): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2476): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2476): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2476): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/SA      ( 6846): [RC New] Execute method=[GET] start
,I/SA      ( 6846): [RC New] Security=[true]
,I/System.out( 6846): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6846): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6846): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/WifiStateMachine(  846): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  846): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  846): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  846): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  846): identical MTU - not setting
,D/ConnectivityService(  846): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  846): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  276): QcRouteController
,V/        (  276): QcRouteController
,W/NetworkManagementService(  846): route cmd failed: 
W/NetworkManagementService(  846): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  846): '
W/NetworkManagementService(  846): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  846): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  846): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  846): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  846): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  846): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  846): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  846): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  846): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  846): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  846): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  846): calling update connectivity
,D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  846): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
,D/ConnectivityService(  846): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  846): calling update connectivity
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  846):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  846): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
,D/SmartBondingService(  846): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  846): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
D/SmartBondingService(  846): getSBEnabled() enabled =false
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6846): [RC New] [v2liruge] api execute + 647
I/SA      ( 6846): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6846): AsyncTask #1 calls detatch()
,I/SA      ( 6846): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6846): [OCP] update openData : PL
,I/SA      ( 6846): [TPMU] getNetworkMcc : 
,I/SA      ( 6846): [SCU] saveMccToPreferece Start
,I/SA      ( 6846): [SCU] RegionMCC : 260
I/SA      ( 6846): [SSP] query invoked
,I/SA      ( 6846): [TPMU] GetMccFromDB : null
,I/SA      ( 6846): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6846): [SCU] saveMccToPreferece End
,I/SA      ( 6846): [RC New] executeRequest [v2liruge] end. 695
I/SA      ( 6846): [RC New] Execute end
I/SA      ( 6846): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6846): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  846): REQUEST_POWER_SAVE_ON
,D/GCM     ( 1692): Connected
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1692): Message class com.google.f.a.a.p
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  846): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7637): wlan0: sending IPv6 Router Solicitation
,D/WearableService( 4902): callingUid 10012, callindPid: 4902
,D/ResourcesManager( 7558): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7558): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7558): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7558): Using the GMSCore's GoogleHttpClient
,D/WearableClient( 7558): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7558): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 7558): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7558): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient( 7558): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 7558): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback( 7558): Conditions not met for autocaching.
I/MusicLeanback( 7558): Stop autocaching.
,E/ActivityThread( 7558): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3d728695 that was originally bound here
E/ActivityThread( 7558): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3d728695 that was originally bound here
E/ActivityThread( 7558): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7558): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7558): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2085)
E/ActivityThread( 7558): 	at android.app.ContextImpl.bindService(ContextImpl.java:2068)
E/ActivityThread( 7558): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7558): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread( 7558): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7558): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7558): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread( 7558): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread( 7558): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread( 7558): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread( 7558): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread( 7558): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread( 7558): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread( 7558): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 7558): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 7558): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 7558): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7558): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7558): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 7558): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7558): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 7558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/jxcore-log( 7428): Test app app.js loaded
I/jxcore-log( 7428): 
,I/chromium( 7428): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  282): DCD ON
,I/chromium( 7428): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7428): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7428): 
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  249): id=15 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=15 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  846): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 846) eventTime = 106976
,D/PowerManagerService(  846): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=846 (0x0)
D/PowerManagerService(  846): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=846, ws=WorkSource{10059}) (elapsedTime=3488)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/GAV4    ( 7773): Thread[GAThread,5,main]: No campaign data found.
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6808): mConnectivityHandler : connected,
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6808): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6808): ================================================
,I/CSTORAGE( 6808):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6808): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6808): [GetString-S]
,E/art     ( 6808): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6808): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6808): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6808): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6808): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6808): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6808): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7637): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7637): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7637): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7171): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7171): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7171): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7171): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7171): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7171): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7171): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7171): entry::IDLE
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 350, PST = 412, CUR = 300
,D/PreloadUpdateManagerStateMachine( 7171): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7171): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7171): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7171): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7171): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7171): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7171): entry::IDLE
,D/FactoryTest( 6494): Not factory mode
,D/FactoryTest( 6494): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6494): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6494): still no open session command from host, so toast
,W/ContextImpl( 6494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6494): Timeline: Activity_launch_request id:com.android.settings time:114143
,E/PersonaManagerService(  846): inState():  stateMachine is null !!
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  846): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  846): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
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
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6494): started activity for popup
,I/SQLiteSecureOpenHelper( 3578): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3578): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6494): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6494): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6494): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  846): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  846): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@7c70ca0 attribute=null, token = android.os.BinderProxy@3811d633
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6494): dev.kiessupport is : TRUE
,D/Activity( 6494): performCreate Call secproduct feature valuefalse
,D/Activity( 6494): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ActivityManager(  846): post active user change for 0
D/KnoxTimeoutHandler(  846): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  846): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7428): Timeline: Activity_idle id: android.os.BinderProxy@354cb1b8 time:114481
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ActivityManager(  846): mDVFSHelper.release()
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  846): [PWL] Off : 50s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 330, PST = 399, CUR = 300
,D/X       (  846): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1224):  LEVEL : -1
,E/TranscodeReceiver( 7191): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7191):  SIOP_LEVEL: -1
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 4
,D/SSRM:m  (  846): SIOP:: AP = 320, PST = 384, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  846): waitForAlarm result :4
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 4.
,I/art     (  846): Explicit concurrent mark sweep GC freed 47763(2MB) AllocSpace objects, 16(386KB) LOS objects, 30% free, 36MB/52MB, paused 3.456ms total 124.436ms
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  846): SIOP:: AP = 310, PST = 367, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 75s ago
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  846): SIOP:: AP = 310, PST = 354, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6670): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at dsf.a(PG:807)
E/HttpOperation( 6670): 	at fhk.a(PG:1126)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 8 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 10 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6670): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at ieo.a(PG:43)
E/HttpOperation( 6670): 	at iep.a(PG:93)
E/HttpOperation( 6670): 	at fhn.a(PG:59)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/ExperimentLoader( 6670): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): 	at kfv.a(PG:65)
E/ExperimentLoader( 6670): 	at kff.u(PG:385)
E/ExperimentLoader( 6670): 	at kfb.a(PG:29)
E/ExperimentLoader( 6670): 	at kff.l(PG:132)
E/ExperimentLoader( 6670): 	at ieo.a(PG:43)
E/ExperimentLoader( 6670): 	at iep.a(PG:93)
E/ExperimentLoader( 6670): 	at fhn.a(PG:59)
E/ExperimentLoader( 6670): 	at lex.a(PG:85)
E/ExperimentLoader( 6670): 	at lex.b(PG:132)
E/ExperimentLoader( 6670): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6670): 	at fhk.a(PG:908)
E/ExperimentLoader( 6670): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6670): 	at ihi.a(PG:22)
E/ExperimentLoader( 6670): 	at kft.a(PG:91)
E/ExperimentLoader( 6670): 	at kfv.a(PG:62)
E/ExperimentLoader( 6670): 	... 12 more
E/ExperimentLoader( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6670): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6670): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6670): 	at ihi.a(PG:19)
E/ExperimentLoader( 6670): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6670): [getaccountstatus] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at ixd.a(PG:248)
E/HttpOperation( 6670): 	at ixd.b(PG:206)
E/HttpOperation( 6670): 	at ixd.a(PG:175)
E/HttpOperation( 6670): 	at fig.a(PG:78)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/EsSyncAdapterService( 6670): Sync failure
E/EsSyncAdapterService( 6670): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6670): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6670): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6670): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6670): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6670): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6670): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6670): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6670): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6670): 	... 10 more
E/EsSyncAdapterService( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6670): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6670): 	... 12 more
E/EsSyncAdapterService( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6670): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6670): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6670): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 156613, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  846): mCursor = null
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  846): waitForAlarm result :4
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 5.
,W/ProcessCpuTracker(  846): Skipping unknown process pid 8070
,W/ProcessCpuTracker(  846): Skipping unknown process pid 8071
,W/ProcessCpuTracker(  846): Skipping unknown process pid 8073
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 5
,D/SSRM:m  (  846): SIOP:: AP = 300, PST = 343, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  846): stay LED for fully charged
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON,
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 300, PST = 332, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 105s ago
,V/AlarmManager(  846): waitForAlarm result :8
,V/AlarmManager(  846): waitForAlarm result :4
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): stay LED for fully charged
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1692): Vacuum at: now=1452019322296 tag=VacuumService
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1692): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/System.out( 1692): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1692): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1692): (HTTPLog)-Thread-207-939386391: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6697): [1] 5.onFinished: Giving up after 6 failures.
,I/qtaguid ( 1692): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692):  no longer exists, so no auth token.
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 300, PST = 326, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 55984(3MB) AllocSpace objects, 59(3MB) LOS objects, 40% free, 18MB/30MB, paused 622us total 54.124ms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6937037163267293458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6937037163267293458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6937037163267293458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6937037163267293458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6937037163267293458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158645, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  846): Explicit concurrent mark sweep GC freed 40971(2MB) AllocSpace objects, 24(839KB) LOS objects, 30% free, 36MB/52MB, paused 1.745ms total 132.191ms
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  846): mCursor = null
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6670): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at dsf.a(PG:807)
E/HttpOperation( 6670): 	at fhk.a(PG:1126)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 8 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6670): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at ieo.a(PG:43)
E/HttpOperation( 6670): 	at iep.a(PG:93)
E/HttpOperation( 6670): 	at fhn.a(PG:59)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/ExperimentLoader( 6670): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): 	at kfv.a(PG:65)
E/ExperimentLoader( 6670): 	at kff.u(PG:385)
E/ExperimentLoader( 6670): 	at kfb.a(PG:29)
E/ExperimentLoader( 6670): 	at kff.l(PG:132)
E/ExperimentLoader( 6670): 	at ieo.a(PG:43)
E/ExperimentLoader( 6670): 	at iep.a(PG:93)
E/ExperimentLoader( 6670): 	at fhn.a(PG:59)
E/ExperimentLoader( 6670): 	at lex.a(PG:85)
E/ExperimentLoader( 6670): 	at lex.b(PG:132)
E/ExperimentLoader( 6670): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6670): 	at fhk.a(PG:908)
E/ExperimentLoader( 6670): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6670): 	at ihi.a(PG:22)
E/ExperimentLoader( 6670): 	at kft.a(PG:91)
E/ExperimentLoader( 6670): 	at kfv.a(PG:62)
E/ExperimentLoader( 6670): 	... 12 more
E/ExperimentLoader( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6670): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6670): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6670): 	at ihi.a(PG:19)
E/ExperimentLoader( 6670): 	... 14 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6670): [getaccountstatus] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at ixd.a(PG:248)
E/HttpOperation( 6670): 	at ixd.b(PG:206)
E/HttpOperation( 6670): 	at ixd.a(PG:175)
E/HttpOperation( 6670): 	at fig.a(PG:78)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/EsSyncAdapterService( 6670): Sync failure
E/EsSyncAdapterService( 6670): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6670): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6670): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6670): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6670): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6670): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6670): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6670): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6670): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6670): 	... 10 more
E/EsSyncAdapterService( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6670): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6670): 	... 12 more
E/EsSyncAdapterService( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6670): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6670): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6670): 	... 14 more
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 189718, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  846): mCursor = null
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 6
,D/SSRM:m  (  846): SIOP:: AP = 300, PST = 322, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 311, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  846): [PWL] Off : 140s ago
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 305, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 7
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 301, CUR = 300
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 298, CUR = 300
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK,
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  282): DCD ON
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8289721611348087251&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8289721611348087251&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8289721611348087251&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8289721611348087251&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8289721611348087251&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 223311, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  846): mCursor = null
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 8
,I/PowerManagerService(  846): [PWL] Off : 180s ago
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 292, CUR = 300
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/DataBuffer( 2212): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14a25bde)
,I/art     ( 2212): Explicit concurrent mark sweep GC freed 26706(1574KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 18MB/30MB, paused 743us total 60.561ms
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6670): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at dsf.a(PG:807)
E/HttpOperation( 6670): 	at fhk.a(PG:1126)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 8 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 10 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6670): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at ieo.a(PG:43)
E/HttpOperation( 6670): 	at iep.a(PG:93)
E/HttpOperation( 6670): 	at fhn.a(PG:59)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
E/ExperimentLoader( 6670): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): 	at kfv.a(PG:65)
E/ExperimentLoader( 6670): 	at kff.u(PG:385)
E/ExperimentLoader( 6670): 	at kfb.a(PG:29)
E/ExperimentLoader( 6670): 	at kff.l(PG:132)
E/ExperimentLoader( 6670): 	at ieo.a(PG:43)
E/ExperimentLoader( 6670): 	at iep.a(PG:93)
E/ExperimentLoader( 6670): 	at fhn.a(PG:59)
E/ExperimentLoader( 6670): 	at lex.a(PG:85)
E/ExperimentLoader( 6670): 	at lex.b(PG:132)
E/ExperimentLoader( 6670): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6670): 	at fhk.a(PG:908)
E/ExperimentLoader( 6670): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6670): 	at ihi.a(PG:22)
E/ExperimentLoader( 6670): 	at kft.a(PG:91)
E/ExperimentLoader( 6670): 	at kfv.a(PG:62)
E/ExperimentLoader( 6670): 	... 12 more
E/ExperimentLoader( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6670): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6670): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6670): 	at ihi.a(PG:19)
E/ExperimentLoader( 6670): 	... 14 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6670): [getaccountstatus] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at ixd.a(PG:248)
E/HttpOperation( 6670): 	at ixd.b(PG:206)
E/HttpOperation( 6670): 	at ixd.a(PG:175)
E/HttpOperation( 6670): 	at fig.a(PG:78)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/EsSyncAdapterService( 6670): Sync failure
E/EsSyncAdapterService( 6670): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6670): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6670): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6670): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6670): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6670): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6670): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6670): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6670): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6670): 	... 10 more
E/EsSyncAdapterService( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6670): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6670): 	... 12 more
E/EsSyncAdapterService( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6670): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6670): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6670): 	... 14 more
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 256524, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON,
,E/Watchdog(  846): !@Sync 9
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON,
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 225s ago
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/TimaService(  846): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  846): TimaServiceHandler.handleMessage what =1
,D/TimaService(  846): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  846): initializing...
,I/TLC_TIMA_PKM_initialize(  846): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  846): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  846): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  846): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  846): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  846): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  846): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  846): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  846): App is not loaded in QSEE
,D/QSEECOMAPI: (  846): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  846): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  846): Trustlet response is completed
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  846): waitForAlarm result :4
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager(  846): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8262 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8262): MountEmulatedStorage()
,E/Zygote  ( 8262): v2
I/libpersona( 8262): KNOX_SDCARD checking this for 10081
I/libpersona( 8262): KNOX_SDCARD not a persona
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,I/SELinux ( 8262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SELinux ( 8262): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8262): TimaSignature is unavailable
,D/ActivityThread( 8262): Added TimaKeyStore provider
,D/ResourcesManager( 8262): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  846): Killing 6909:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,W/libprocessgroup(  846): failed to open /acct/uid_10098/pid_6909/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  846): waitForAlarm result :4
,I/DBG_DM  ( 3818): [com.wssyncmldm.lllIlIlIIIllIIlIllIl(350/onReceive)] FotaPostpone callback received
,I/DBG_DM  ( 3818): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 3
,D/LightsService(  846): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 846) 
,D/LightsService(  846): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x42 | SvcLED(id=4) set On
,E/LightSensor(  846): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  846): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/DBG_DM  ( 3818): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 3818): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3818): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/DBG_DM  ( 3818): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 3818): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3818): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2f50fb60
,I/DBG_DM  ( 3818): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/art     (  846): Explicit concurrent mark sweep GC freed 51726(3MB) AllocSpace objects, 59(1529KB) LOS objects, 30% free, 36MB/52MB, paused 1.439ms total 101.525ms
,I/DBG_DM  ( 3818): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  846): showStatusBarByNotification() mOpenByNotification=false
,V/BitmapFactory( 1171): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_completion.qmg
,I/DBG_DM  ( 3818): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,V/BitmapFactory( 1171): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_completion.qmg
,D/KnoxNotification( 1171): ----- inflateViews : modified publicViewLocal -----
,I/DBG_DM  ( 3818): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/KnoxNotification( 1171): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1171): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1171): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@a001572
D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/OpenGLRenderer( 3818): Render dirty regions requested: true
,I/PhoneStatusBar( 1171): Icon Only
,I/DBG_DM  ( 3818): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3818): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3818): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PowerManagerService(  846): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=846
,D/PanelView( 1171): There is/are notification(s) 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Adreno-EGL( 3818): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3818): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3818): Build Date: 03/03/15 Tue
I/Adreno-EGL( 3818): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 3818): Remote Branch: 
I/Adreno-EGL( 3818): Local Patches: 
I/Adreno-EGL( 3818): Reconstruct Branch: 
,I/OpenGLRenderer( 3818): Initialized EGL, version 1.4
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/LightSensor(  846): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/LightsService(  846): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  846): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  846): unregisterListener ::   
,D/LightsService(  846): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/OpenGLRenderer( 3818): HWUI protection enabled for context ,  &this =0xafa22088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3818): Enabling debug mode 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2384679274283279648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/SurfaceFlinger(  249): id=16 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  846): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 846) eventTime = 339274
,D/PowerManagerService(  846): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=846 (0x0)
D/PowerManagerService(  846): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=846, ws=WorkSource{1000}) (elapsedTime=3473)
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2384679274283279648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 42151(2MB) AllocSpace objects, 30(2MB) LOS objects, 40% free, 18MB/30MB, paused 817us total 42.761ms
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,E/SMD     (  282): DCD ON
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2384679274283279648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2384679274283279648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2384679274283279648&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 315999, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  846): mCursor = null
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 11
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  846): [PWL] Off : 275s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6697): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6697): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6697): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6697): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6697): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6697): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6697): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6697): Ignoring header User-Agent because its value was null.
,I/System.out( 6697): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6697): (HTTPLog)-Static: isShipBuild true
I/System.out( 6697): (HTTPLog)-Thread-1094-302611669: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  282): DCD ON,
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7428): TAP version 13
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # multiplex can send data
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 12
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 1 String should be length:200
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # basic
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): ok 2 sane
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # another
I/jxcore-log( 7428): 
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): ok 3 sane
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 4 should be equal
I/jxcore-log( 7428): 
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7428): ok 5 null
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 6 (unnamed assert)
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 7 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 8 should not throw
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 9 (unnamed assert)
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 10 (unnamed assert)
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 11 should not throw
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 12 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 13 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 13
,I/PowerManagerService(  846): [PWL] Off : 330s ago
,I/jxcore-log( 7428): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7428): ok 14 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6670): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at dsf.a(PG:807)
E/HttpOperation( 6670): 	at fhk.a(PG:1126)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 8 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 10 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6670): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at ieo.a(PG:43)
E/HttpOperation( 6670): 	at iep.a(PG:93)
E/HttpOperation( 6670): 	at fhn.a(PG:59)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/ExperimentLoader( 6670): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): 	at kfv.a(PG:65)
E/ExperimentLoader( 6670): 	at kff.u(PG:385)
E/ExperimentLoader( 6670): 	at kfb.a(PG:29)
E/ExperimentLoader( 6670): 	at kff.l(PG:132)
E/ExperimentLoader( 6670): 	at ieo.a(PG:43)
E/ExperimentLoader( 6670): 	at iep.a(PG:93)
E/ExperimentLoader( 6670): 	at fhn.a(PG:59)
E/ExperimentLoader( 6670): 	at lex.a(PG:85)
E/ExperimentLoader( 6670): 	at lex.b(PG:132)
E/ExperimentLoader( 6670): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6670): 	at fhk.a(PG:908)
E/ExperimentLoader( 6670): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6670): 	at ihi.a(PG:22)
E/ExperimentLoader( 6670): 	at kft.a(PG:91)
E/ExperimentLoader( 6670): 	at kfv.a(PG:62)
E/ExperimentLoader( 6670): 	... 12 more
E/ExperimentLoader( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6670): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6670): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6670): 	at ihi.a(PG:19)
E/ExperimentLoader( 6670): 	... 14 more
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,E/HttpOperation( 6670): [getaccountstatus] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at ixd.a(PG:248)
E/HttpOperation( 6670): 	at ixd.b(PG:206)
E/HttpOperation( 6670): 	at ixd.a(PG:175)
E/HttpOperation( 6670): 	at fig.a(PG:78)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/EsSyncAdapterService( 6670): Sync failure
E/EsSyncAdapterService( 6670): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6670): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6670): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6670): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6670): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6670): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6670): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6670): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6670): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6670): 	... 10 more
E/EsSyncAdapterService( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6670): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6670): 	... 12 more
E/EsSyncAdapterService( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6670): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6670): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6670): 	... 14 more
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 407830, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2858): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # failed to get mobile documents path
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7428): ok 15 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 16 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 17 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 18 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # #init should register the networkChanged event
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 19 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7428): # #startBroadcasting should throw on null device name
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 14
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7428): ok 20 should throw
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7428): 
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 21 should throw
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7428): 
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 22 should throw
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7428): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 23 should throw
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # #startBroadcasting should throw on negative port
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 15
,I/PowerManagerService(  846): [PWL] Off : 390s ago
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7428): ok 24 should throw
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # #startBroadcasting should throw on too large port
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7584577601994844160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7584577601994844160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7584577601994844160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7584577601994844160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7584577601994844160&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 470887, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2858): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2858): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  846): Explicit concurrent mark sweep GC freed 46953(2MB) AllocSpace objects, 54(1514KB) LOS objects, 30% free, 36MB/52MB, paused 1.944ms total 179.803ms
D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300,
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 25 should throw
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0,
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000,
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 26 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 27 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 28 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/bootchecker(  326): bootchecker wake up!!
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 29 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 30 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 31 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 16
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 32 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 33 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 34 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 35 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7428): 
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 36 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 37 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 38 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 39 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 40 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 17
,D/SSRM:m  (  846): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/PowerManagerService(  846): [PWL] Off : 455s ago
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/jxcore-log( 7428): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,I/ServiceManager(  338): Waiting for service AtCmdFwd...
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  338): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 280, PST = 288, CUR = 300
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 41 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 42 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 286, CUR = 300
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,I/jxcore-log( 7428): ok 43 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): ok 44 should be equal
I/jxcore-log( 7428): 
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7428): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7428): 
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 18
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 284, CUR = 300
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  338): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  338): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7428): # teardown
I/jxcore-log( 7428): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019698774.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019698774.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback,
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c51a85c
D/BluetoothSocket( 7428): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
,I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019698774.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019698774.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019698774.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019698774.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  846): InactiveState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
D/WifiP2pService(  846): P2pEnabledState add service
,D/WifiP2pService(  846): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
,D/WifiP2pService(  846): InactiveState{ what=139265 }
D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  846): callSECApi what=74
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  846): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
,I/jxcore-log( 7428): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
,I/io.jxcore.node.ConnectionHelper( 7428): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@94fc0eb, channel: 6, state: LISTENING
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@94fc0eb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c51a85c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@247eee48mSocket: android.net.LocalSocket@a5594e1 impl:android.net.LocalSocketImpl@d32206 fd:FileDescriptor[113]
,D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@a5594e1 impl:android.net.LocalSocketImpl@d32206 fd:FileDescriptor[113]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
D/WifiP2pService(  846): InactiveState{ what=139298 }
D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
D/WifiP2pService(  846): P2pEnabledState clear service
D/WifiP2pService(  846): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
D/WifiP2pService(  846): InactiveState{ what=139268 }
I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
D/WifiP2pService(  846): InactiveState{ what=147493 }
D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
D/WifiP2pService(  846): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
D/WifiP2pService(  846): InactiveState{ what=139307 }
D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
D/WifiP2pService(  846): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
I/jxcore-log( 7428): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019698951.7428
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019698951.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b8a6f4
D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019698951.7428
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019698951.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019698951.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019698951.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  846): InactiveState{ what=139292 }
D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
D/WifiP2pService(  846): P2pEnabledState add service
D/WifiP2pService(  846): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
D/WifiP2pService(  846): InactiveState{ what=139265 }
D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  846): callSECApi what=74
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService(  846): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
I/jxcore-log( 7428): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
I/io.jxcore.node.ConnectionHelper( 7428): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@9516263, channel: 6, state: LISTENING
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@9516263, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b8a6f4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f333e60mSocket: android.net.LocalSocket@2412ff19 impl:android.net.LocalSocketImpl@c266bde fd:FileDescriptor[113]
D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@2412ff19 impl:android.net.LocalSocketImpl@c266bde fd:FileDescriptor[113]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
D/WifiP2pService(  846): InactiveState{ what=139298 }
D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
D/WifiP2pService(  846): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
D/WifiP2pService(  846): remove client information from framework
D/WifiP2pService(  846): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
D/WifiP2pService(  846): InactiveState{ what=147493 }
D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
D/WifiP2pService(  846): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  846): InactiveState{ what=139307 }
D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
D/WifiP2pService(  846): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
I/jxcore-log( 7428): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699012.7428
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699012.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2afde08c
D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699012.7428
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699012.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699012.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699012.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  846): InactiveState{ what=139292 }
D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
D/WifiP2pService(  846): P2pEnabledState add service
D/WifiP2pService(  846): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  846): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
I/WifiStateMachine(  846): callSECApi what=74
D/WifiP2pService(  846): discovery change broadcast true
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 7428): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
,I/io.jxcore.node.ConnectionHelper( 7428): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@21c6badb, channel: 6, state: LISTENING
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@21c6badb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2afde08c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@eee7978mSocket: android.net.LocalSocket@2f5c7851 impl:android.net.LocalSocketImpl@36ae18b6 fd:FileDescriptor[113]
D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@2f5c7851 impl:android.net.LocalSocketImpl@36ae18b6 fd:FileDescriptor[113]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
D/WifiP2pService(  846): InactiveState{ what=139298 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
D/WifiP2pService(  846): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
,D/WifiP2pService(  846): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
,D/WifiP2pService(  846): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
I/wpa_supplicant( 1288): P2P-FIND-STOPPED ,
I/jxcore-log( 7428): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
,D/WifiP2pService(  846): InactiveState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699058.7428
D/WifiP2pService(  846): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
,D/WifiP2pService(  846): InactiveState{ what=147493 }
D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  846): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699058.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b4db524
D/BluetoothSocket( 7428): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
,I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699058.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699058.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699058.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699058.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
D/WifiP2pService(  846): InactiveState{ what=139292 }
I/jxcore-log( 7428): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
I/io.jxcore.node.ConnectionHelper( 7428): stop
D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
D/WifiP2pService(  846): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
,D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@288faa53, channel: 6, state: LISTENING
D/WifiP2pService(  846): add a new client
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@288faa53, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b4db524, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a42ff90mSocket: android.net.LocalSocket@11c4e089 impl:android.net.LocalSocketImpl@33888e fd:FileDescriptor[113]
,D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@11c4e089 impl:android.net.LocalSocketImpl@33888e fd:FileDescriptor[113]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
,D/WifiP2pService(  846): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
,D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
,D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
I/jxcore-log( 7428): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE,
I/WifiStateMachine(  846): callSECApi what=74
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
,D/WifiP2pService(  846): discovery change broadcast true
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699092.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
D/WifiP2pService(  846): InactiveState{ what=139298 }
I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699092.7428","ra":"B0:C5:59:3F:75:69"}
D/WifiP2pService(  846): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback,
,D/WifiP2pService(  846): remove client information from framework
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f0084bc
,D/WifiP2pService(  846): InactiveState{ what=139268 }
D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
,I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699092.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
,D/WifiP2pService(  846): InactiveState{ what=139307 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699092.7428","ra":"B0:C5:59:3F:75:69"}
,D/WifiP2pService(  846): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,D/WifiP2pService(  846): InactiveState{ what=147493 }
D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
D/WifiP2pService(  846): discovery change broadcast false,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699092.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699092.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  846): InactiveState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState add service
D/WifiP2pService(  846): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
,D/WifiP2pService(  846): InactiveState{ what=139265 }
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
,I/jxcore-log( 7428): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
,I/WifiStateMachine(  846): callSECApi what=74
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
,I/io.jxcore.node.ConnectionHelper( 7428): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
,D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@13a810cb, channel: 6, state: LISTENING
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@13a810cb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f0084bc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1baf30a8mSocket: android.net.LocalSocket@345b17c1 impl:android.net.LocalSocketImpl@2c4c1b66 fd:FileDescriptor[113]
D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@345b17c1 impl:android.net.LocalSocketImpl@2c4c1b66 fd:FileDescriptor[113]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
D/WifiP2pService(  846): discovery change broadcast true,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
,D/WifiP2pService(  846): InactiveState{ what=139298 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  846): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
,I/jxcore-log( 7428): ok 54 Should be able to call stopBroadcasting without error
,I/jxcore-log( 7428): 
,D/WifiP2pService(  846): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
D/WifiP2pService(  846): InactiveState{ what=139268 }
,I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699142.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69,
D/WifiP2pService(  846): InactiveState{ what=139307 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  846): P2pEnabledState clear service request,
,D/WifiP2pService(  846): InactiveState{ what=147493 }
,D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699142.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
,D/WifiP2pService(  846): discovery change broadcast false
W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]},
D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
,D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a1aaf54
,D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
,I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699142.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699142.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699142.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699142.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  846): InactiveState{ what=139292 },
D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService(  846): add a new client
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7428): start: OK
I/jxcore-log( 7428): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
,D/WifiP2pService(  846): InactiveState{ what=139265 }
,I/io.jxcore.node.ConnectionHelper( 7428): stop
D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
,I/WifiStateMachine(  846): callSECApi what=74
D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@20a7ce43, channel: 6, state: LISTENING,
D/WifiP2pService(  846): discovery change broadcast true
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@20a7ce43, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a1aaf54, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@131d6cc0mSocket: android.net.LocalSocket@3729fdf9 impl:android.net.LocalSocketImpl@2fd9313e fd:FileDescriptor[113]
,D/WifiP2pService(  846): InactiveState{ what=139298 }
I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@3729fdf9 impl:android.net.LocalSocketImpl@2fd9313e fd:FileDescriptor[113],
D/WifiP2pService(  846): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
,I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
,D/WifiP2pService(  846): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
,D/WifiP2pService(  846): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/WifiP2pService(  846): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
,I/jxcore-log( 7428): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
,D/WifiP2pService(  846): P2pEnabledState clear service request
I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
D/WifiP2pService(  846): InactiveState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
,D/WifiP2pService(  846): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699182.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699182.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cc94ec
D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699182.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699182.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699182.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699182.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  846): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
,D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
,I/jxcore-log( 7428): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
,I/io.jxcore.node.ConnectionHelper( 7428): stop
D/WifiP2pService(  846): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@2c42c2bb, channel: 6, state: LISTENING
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@2c42c2bb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cc94ec, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@76413d8mSocket: android.net.LocalSocket@14b87331 impl:android.net.LocalSocketImpl@e882a16 fd:FileDescriptor[113]
D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@14b87331 impl:android.net.LocalSocketImpl@e882a16 fd:FileDescriptor[113]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
,D/WifiP2pService(  846): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
,I/jxcore-log( 7428): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
,D/WifiP2pService(  846): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699220.7428
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
,D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
,D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  846): callSECApi what=74
,D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699220.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
,D/WifiP2pService(  846): discovery change broadcast true
,W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService(  846): InactiveState{ what=139298 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f29584
D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
,D/WifiP2pService(  846): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699220.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
,D/WifiP2pService(  846): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699220.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,D/WifiP2pService(  846): InactiveState{ what=139268 }
,I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699220.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699220.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  846): InactiveState{ what=139307 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  846): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
,D/WifiP2pService(  846): InactiveState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
D/WifiP2pService(  846): discovery change broadcast false
,D/WifiP2pService(  846): InactiveState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState add service
,D/WifiP2pService(  846): add a new client
,D/WifiP2pService(  846): InactiveState{ what=139265 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
,I/WifiStateMachine(  846): callSECApi what=74
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService(  846): discovery change broadcast true
,I/jxcore-log( 7428): ok 59 Should be able to call startBroadcasting without error,
I/jxcore-log( 7428): 
I/io.jxcore.node.ConnectionHelper( 7428): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@39c8ce33, channel: 6, state: LISTENING
,D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@39c8ce33, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f29584, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37c585f0mSocket: android.net.LocalSocket@35895769 impl:android.net.LocalSocketImpl@285265ee fd:FileDescriptor[113]
D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@35895769 impl:android.net.LocalSocketImpl@285265ee fd:FileDescriptor[113]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/WifiP2pService(  846): InactiveState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
D/WifiP2pService(  846): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
D/WifiP2pService(  846): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
,I/jxcore-log( 7428): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
D/WifiP2pService(  846): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699297.7428,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
,D/WifiP2pService(  846): InactiveState{ what=139307 }
D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  846): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
,D/WifiP2pService(  846): InactiveState{ what=147493 }
,D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  846): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699297.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b95111c
,D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699297.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699297.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699297.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699297.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  846): InactiveState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  846): P2pEnabledState add service
,D/WifiP2pService(  846): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
,D/WifiP2pService(  846): InactiveState{ what=139265 }
,I/jxcore-log( 7428): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
,D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 7428): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@2aa5d0ab, channel: 6, state: LISTENING
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@2aa5d0ab, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b95111c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d702308mSocket: android.net.LocalSocket@339b8aa1 impl:android.net.LocalSocketImpl@36fd44c6 fd:FileDescriptor[113]
D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@339b8aa1 impl:android.net.LocalSocketImpl@36fd44c6 fd:FileDescriptor[113]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
,I/WifiStateMachine(  846): callSECApi what=74
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService(  846): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
,D/WifiP2pService(  846): InactiveState{ what=139298 }
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/WifiP2pService(  846): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
,I/jxcore-log( 7428): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
D/WifiP2pService(  846): remove client information from framework
,D/WifiP2pService(  846): InactiveState{ what=139268 }
,I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setDiscoveryMode: Mode set to WIFI
,D/WifiP2pService(  846): InactiveState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699383.7428
D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): bind: Binding a new listener
,D/WifiP2pService(  846): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): initialize: My bluetooth address is B0:C5:59:3F:75:69
D/WifiP2pService(  846): InactiveState{ what=147493 }
,D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  846): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699383.7428","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7428): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7428): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 7428): bindListen(), new LocalSocket 
D/BluetoothSocket( 7428): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7428): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e6867b4
,D/BluetoothSocket( 7428): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): start: OK
I/io.jxcore.node.ConnectionHelper( 7428): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: Peer ID: B0:C5:59:3F:75:69, peer name: 1452019699383.7428
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7428): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699383.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): start: {"pi":"B0:C5:59:3F:75:69","pn":"1452019699383.7428","ra":"B0:C5:59:3F:75:69"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"1452019699383.7428","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  846): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): start: OK
,D/WifiP2pService(  846): P2pEnabledState{ what=139292 }
I/jxcore-log( 7428): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 7428): 
,I/io.jxcore.node.ConnectionHelper( 7428): stop
D/WifiP2pService(  846): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): shutdown
,D/BluetoothSocket( 7428): close() in, this: android.bluetooth.BluetoothSocket@25e1aa23, channel: 6, state: LISTENING
D/WifiP2pService(  846): add a new client
D/BluetoothSocket( 7428): close() this: android.bluetooth.BluetoothSocket@25e1aa23, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e6867b4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1cfe4b20mSocket: android.net.LocalSocket@de9ecd9 impl:android.net.LocalSocketImpl@3b9a269e fd:FileDescriptor[113]
,D/BluetoothSocket( 7428): Closing mSocket: android.net.LocalSocket@de9ecd9 impl:android.net.LocalSocketImpl@3b9a269e fd:FileDescriptor[113]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7428): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7428): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7428): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7428): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): stop: Stopping P2P device discovery...
,D/WifiP2pService(  846): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7428): release: No more listeners, de-initializing...
,D/WifiP2pService(  846): P2pEnabledState{ what=139265 }
D/WifiService(  846): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  846): callSECApi what=74
D/WifiStateMachine(  846): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  846): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1288): USE_NETWORK : USE_NETWORK OFF
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7428): release: No more listeners, de-initializing...
I/wpa_supplicant( 1288): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7428): setState: NOT_STARTED
,I/jxcore-log( 7428): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 7428): 
,D/WifiP2pService(  846): discovery change broadcast true
,D/WifiP2pService(  846): InactiveState{ what=139298 }
,D/WifiP2pService(  846): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  846): P2pEnabledState clear service
,D/WifiP2pService(  846): remove client information from framework
,I/jxcore-log( 7428): # setup
I/jxcore-log( 7428): 
,D/WifiP2pService(  846): InactiveState{ what=139268 }
I/wpa_supplicant( 1288): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
,D/WifiP2pService(  846): InactiveState{ what=139307 }
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
,D/WifiP2pService(  846): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
D/WifiP2pService(  846): P2pEnabledState clear service request
,I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService(  846): InactiveState{ what=147493 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
,D/WifiP2pService(  846): P2pEnabledState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
,D/WifiP2pService(  846): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7428): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 7428): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7428): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7428): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7428): Service requests cleared successfully
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 284, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/Atfwd_Daemon(  338): Stop the daemon....
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 19
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 525s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  846): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  846): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  846): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  846): SIOP:: AP = 290, PST = 276, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 280, PST = 276, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ActivityManager(  846): Killing 6971:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,W/libprocessgroup(  846): failed to open /acct/uid_10033/pid_6971/cgroup.procs: No such file or directory
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 21
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available,
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6670): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at dsf.a(PG:807)
E/HttpOperation( 6670): 	at fhk.a(PG:1126)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 8 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/HttpOperation( 6670): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at ieo.a(PG:43)
E/HttpOperation( 6670): 	at iep.a(PG:93)
E/HttpOperation( 6670): 	at fhn.a(PG:59)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/ExperimentLoader( 6670): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): 	at kfv.a(PG:65)
E/ExperimentLoader( 6670): 	at kff.u(PG:385)
E/ExperimentLoader( 6670): 	at kfb.a(PG:29)
E/ExperimentLoader( 6670): 	at kff.l(PG:132)
E/ExperimentLoader( 6670): 	at ieo.a(PG:43)
E/ExperimentLoader( 6670): 	at iep.a(PG:93)
E/ExperimentLoader( 6670): 	at fhn.a(PG:59)
E/ExperimentLoader( 6670): 	at lex.a(PG:85)
E/ExperimentLoader( 6670): 	at lex.b(PG:132)
E/ExperimentLoader( 6670): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6670): 	at fhk.a(PG:908)
E/ExperimentLoader( 6670): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6670): 	at ihi.a(PG:22)
E/ExperimentLoader( 6670): 	at kft.a(PG:91)
E/ExperimentLoader( 6670): 	at kfv.a(PG:62)
E/ExperimentLoader( 6670): 	... 12 more
E/ExperimentLoader( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6670): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6670): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6670): 	at ihi.a(PG:19)
E/ExperimentLoader( 6670): 	... 14 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6670): [getaccountstatus] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at ixd.a(PG:248)
E/HttpOperation( 6670): 	at ixd.b(PG:206)
E/HttpOperation( 6670): 	at ixd.a(PG:175)
E/HttpOperation( 6670): 	at fig.a(PG:78)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/EsSyncAdapterService( 6670): Sync failure
E/EsSyncAdapterService( 6670): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6670): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6670): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6670): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6670): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6670): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6670): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6670): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6670): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6670): 	... 10 more
E/EsSyncAdapterService( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6670): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6670): 	... 12 more
E/EsSyncAdapterService( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6670): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6670): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6670): 	... 14 more
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 667757, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 22
,I/PowerManagerService(  846): [PWL] Off : 600s ago
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 23
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SMD     (  282): DCD ON
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,E/Watchdog(  846): !@Sync 24
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8547630567578194288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8547630567578194288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8547630567578194288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8547630567578194288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8547630567578194288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 733287, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  846): mCursor = null
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON,
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 680s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 25
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 26
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 269, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 27
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 268, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 267, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 765s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 28
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 29
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  846): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  846): TimaServiceHandler.handleMessage what =1
,D/TimaService(  846): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 855s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/Finsky  ( 6697): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/LightsService(  846): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,E/LightSensor(  846): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  846): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 38425(2MB) AllocSpace objects, 31(2MB) LOS objects, 39% free, 18MB/30MB, paused 856us total 43.520ms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6697): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  846): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/LightsService(  846): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  846): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  846): unregisterListener ::   
D/LightsService(  846): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/art     (  846): Explicit concurrent mark sweep GC freed 62711(4MB) AllocSpace objects, 146(2MB) LOS objects, 30% free, 36MB/52MB, paused 7.621ms total 144.226ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6697): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6697): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6697): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6697): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6697): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 2212): client connected with version: 7571000
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 31
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 32
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 33
,V/AlarmManager(  846): waitForAlarm result :4
,D/GCM     ( 1692): Message class com.google.f.a.a.i
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 266, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 950s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 265, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 34
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6697): [1] 5.onFinished: Scheduling replication attempt 5.
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 35
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6697): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6697): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 36
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 37
,I/PowerManagerService(  846): [PWL] Off : 1050s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  846): stay LED for fully charged
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 38
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 39
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6670): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at dsf.a(PG:807)
E/HttpOperation( 6670): 	at fhk.a(PG:1126)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 8 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 10 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
D/SecContentProvider2(  846): mCursor = null
,D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6670): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at kff.l(PG:132)
E/HttpOperation( 6670): 	at ieo.a(PG:43)
E/HttpOperation( 6670): 	at iep.a(PG:93)
E/HttpOperation( 6670): 	at fhn.a(PG:59)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
E/ExperimentLoader( 6670): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6670): 	at kfv.a(PG:65)
E/ExperimentLoader( 6670): 	at kff.u(PG:385)
E/ExperimentLoader( 6670): 	at kfb.a(PG:29)
E/ExperimentLoader( 6670): 	at kff.l(PG:132)
E/ExperimentLoader( 6670): 	at ieo.a(PG:43)
E/ExperimentLoader( 6670): 	at iep.a(PG:93)
E/ExperimentLoader( 6670): 	at fhn.a(PG:59)
E/ExperimentLoader( 6670): 	at lex.a(PG:85)
E/ExperimentLoader( 6670): 	at lex.b(PG:132)
E/ExperimentLoader( 6670): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6670): 	at fhk.a(PG:908)
E/ExperimentLoader( 6670): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6670): 	at ihi.a(PG:22)
E/ExperimentLoader( 6670): 	at kft.a(PG:91)
E/ExperimentLoader( 6670): 	at kfv.a(PG:62)
E/ExperimentLoader( 6670): 	... 12 more
E/ExperimentLoader( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6670): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6670): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6670): 	at ihi.a(PG:19)
E/ExperimentLoader( 6670): 	... 14 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6670): [getaccountstatus] Unexpected exception
E/HttpOperation( 6670): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6670): 	at kfv.a(PG:65)
E/HttpOperation( 6670): 	at kff.u(PG:385)
E/HttpOperation( 6670): 	at kfb.a(PG:29)
E/HttpOperation( 6670): 	at ixd.a(PG:248)
E/HttpOperation( 6670): 	at ixd.b(PG:206)
E/HttpOperation( 6670): 	at ixd.a(PG:175)
E/HttpOperation( 6670): 	at fig.a(PG:78)
E/HttpOperation( 6670): 	at lex.a(PG:85)
E/HttpOperation( 6670): 	at lex.b(PG:132)
E/HttpOperation( 6670): 	at fhk.a(PG:1146)
E/HttpOperation( 6670): 	at fhk.a(PG:908)
E/HttpOperation( 6670): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6670): 	at ihi.a(PG:22)
E/HttpOperation( 6670): 	at kft.a(PG:91)
E/HttpOperation( 6670): 	at kfv.a(PG:62)
E/HttpOperation( 6670): 	... 12 more
E/HttpOperation( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6670): 	at gde.c(Unknown Source)
E/HttpOperation( 6670): 	at gde.b(Unknown Source)
E/HttpOperation( 6670): 	at ihi.a(PG:19)
E/HttpOperation( 6670): 	... 14 more
,E/EsSyncAdapterService( 6670): Sync failure
E/EsSyncAdapterService( 6670): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6670): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6670): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6670): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6670): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6670): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6670): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6670): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6670): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6670): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6670): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6670): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6670): 	... 10 more
E/EsSyncAdapterService( 6670): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6670): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6670): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6670): 	... 12 more
E/EsSyncAdapterService( 6670): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6670): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6670): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6670): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6670): 	... 14 more
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1186813, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  846): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  846): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  846): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  846): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  846): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  846): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  846): Updating Usage Statistics in DB @ 1452020352270
,I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
,W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
,W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
,W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
,W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
,W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
,W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  846): ::getAppControlDB: Exception to create DB
W/System.err(  846): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  846): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  846): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  846): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  846): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  846): Done Updating Usage Statistics in DB @ 1452020352528
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 1155s ago
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 41
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  846): stay LED for fully charged
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2232840759130327030&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2232840759130327030&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 37586(2MB) AllocSpace objects, 12(972KB) LOS objects, 40% free, 18MB/30MB, paused 833us total 91.826ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  846): uri = 14 selection = getSealedState
,D/SecContentProvider2(  846): mCursor = null
D/SecContentProvider2(  846): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  846): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  846): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2232840759130327030&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1171): Explicit concurrent mark sweep GC freed 88612(4MB) AllocSpace objects, 60(5MB) LOS objects, 30% free, 37MB/53MB, paused 852us total 111.197ms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2232840759130327030&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=2232840759130327030&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SyncManager(  846): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1254402, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  846): Explicit concurrent mark sweep GC freed 74855(5MB) AllocSpace objects, 109(2MB) LOS objects, 30% free, 36MB/52MB, paused 2.211ms total 174.809ms
D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
,D/SSRM:m  (  846): SIOP:: AP = 270, PST = 262, CUR = 300
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 42
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 43
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,V/AlarmManager(  846): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,D/BatteryService(  846): stay LED for fully charged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 44
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 1265s ago
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,D/BatteryService(  846): stay LED for fully charged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 45
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 46
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 47
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 48
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 1380s ago
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  846): stay LED for fully charged
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 49
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  846): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  846): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  846): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  846): !@Sync 50
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 51
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  846): stay LED for fully charged
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 52
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 1500s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  846): !@Sync 53
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,D/BatteryService(  846): stay LED for fully charged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 54
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 55
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :8
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 56
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 1625s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 57
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 58
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 59
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,D/BatteryService(  846): stay LED for fully charged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/NetworkStatsFactory(  846): UpdateStatsForKnox
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/TimaService(  846): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  846): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  846): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 60
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  846): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  846): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  846): [PWL] Off : 1755s ago
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 61
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  846): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  846): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  846): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  846):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  846): Plugged
,I/MotionRecognitionService(  846): setPowerConnected  = true
,D/BatteryService(  846): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3251): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3251): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 62
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  846): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  846): !@Sync 63
,E/SMD     (  282): DCD ON
,V/AlarmManager(  846): waitForAlarm result :4
,D/LightsService(  846): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  846): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  846): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ActivityManager(  846): Killing 7499:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7853:com.android.email/u0a163 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7837:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7773:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7751:com.android.chrome/u0a88 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 6633:com.sec.chaton/u0a86 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7725:com.sec.knox.bridge/1000 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7695:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 6846:com.osp.app.signin/u0a45 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 6825:com.policydm/1000 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7668:com.sec.android.soagent/u0a37 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7653:com.samsung.klmsagent/u0a19 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7631:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7612:com.sec.android.diagmonagent/1000 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7593:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 6808:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,I/ActivityManager(  846): Killing 7875:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1802s
,I/ActivityManager(  846): Killing 7252:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): empty for 1832s
,I/ActivityManager(  846): Killing 5026:com.android.defcontainer/u0a5 (adj 15): empty for 1836s
,I/ActivityManager(  846): Killing 7151:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1844s
,I/ActivityManager(  846): Killing 6739:com.google.android.gms:car/u0a12 (adj 15): empty for 1844s
,I/ActivityManager(  846): Killing 7130:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1844s
,I/ActivityManager(  846): Killing 7093:com.samsung.helphub/1000 (adj 15): empty for 1844s
I/ActivityManager(  846): Killing 7077:com.samsung.android.magazine.service/u0a118 (adj 15): empty for 1844s
,I/ActivityManager(  846): Killing 7059:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): empty for 1844s
,I/ActivityManager(  846): Killing 7030:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1844s
,I/ActivityManager(  846): Killing 7018:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1845s
,I/ActivityManager(  846): Killing 7007:com.sec.android.provider.logsprovider/u0a20 (adj 15): empty for 1845s
,I/ActivityManager(  846): Killing 6935:com.sec.android.automotive.drivelink/u0a99 (adj 15): empty for 1845s
,I/ProcessStatsService(  846): Prepared write state in 15ms
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,V/NetworkStats(  846): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  846): UpdateStatsForKnox
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/ConnectivityService(  846): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  846): performPollLocked() took 23ms
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/NtpTrustedTime(  846): currentTimeMillis() cache hit
D/NtpTrustedTime(  846): currentTimeMillis() cache hit
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1692): Message class com.google.f.a.a.i
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  846): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  846): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/LightsService(  846): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  846): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  846): unregisterListener ::   
,D/LightsService(  846): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/EventLogService( 2476): Aggregate from 1452018802665 (log), 1452018802665 (data)
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  846): Pruning old procstats: /data/system/procstats/state-2016-01-05-02-51-02.bin
,W/libprocessgroup(  846): failed to open /acct/uid_10088/pid_7751/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7499/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10166/pid_7130/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7612/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7093/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7030/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6825/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10045/pid_6846/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10086/pid_6633/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_7725/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10138/pid_7837/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10078/pid_7875/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10163/pid_7853/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10112/pid_7059/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10011/pid_7631/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10170/pid_7151/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10005/pid_5026/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_1000/pid_6808/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10020/pid_7007/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10003/pid_7018/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10019/pid_7653/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10118/pid_7077/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10012/pid_6739/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10158/pid_7252/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10071/pid_7695/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10037/pid_7668/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10002/pid_7593/cgroup.procs: No such file or directory
,W/libprocessgroup(  846): failed to open /acct/uid_10128/pid_7773/cgroup.procs: No such file or directory
W/libprocessgroup(  846): failed to open /acct/uid_10099/pid_6935/cgroup.procs: No such file or directory
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8818): 
D/AndroidRuntime( 8818): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8818): CheckJNI is OFF
D/AndroidRuntime( 8818): setted country_code = Germany
D/AndroidRuntime( 8818): setted countryiso_code = DE
D/AndroidRuntime( 8818): setted sales_code = DBT
D/AndroidRuntime( 8818): readGMSProperty: start
D/AndroidRuntime( 8818): readGMSProperty: already setted!!
D/AndroidRuntime( 8818): readGMSProperty: end
D/AndroidRuntime( 8818): addProductProperty: start
E/AffinityControl( 8818): AffinityControl: registerfunction enter
D/AndroidRuntime( 8818): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  846): START PACKAGE DELETE: observer{702735541}
D/PackageManager(  846): pkg{<packageName>}
D/PackageManager(  846): user{0}
D/PackageManager(  846): caller{2000}
D/PackageManager(  846): flags{3}
D/PersonaManagerService(  846): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  846): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  846): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  846): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  846): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  846): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  846): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  846): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  846): getApplicationUninstallationEnabled
D/ApplicationPolicy(  846): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  846): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  846): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  846): Killing 7428:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  846):   Force finishing activity ActivityRecord{3f34c79a u0 com.test.thalitest/.MainActivity t11}
D/FocusedStackFrame(  846): Set to : 0
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
D/ConnectivityService(  846): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/PackageSettings(  846): Skipping PackageSetting{3b67abad com.example.hello/10375} due to missing metadata
D/WifiService(  846): Client connection lost with reason: 4
I/ActivityManager(  846): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 1568): Explicit concurrent mark sweep GC freed 1829(82KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 1.084ms total 37.081ms
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/art     ( 4484): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 840us total 69.745ms
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager( 1478): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
E/SamsungIME( 1870): mOCRHelper is null
I/InputReader(  846): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/GeofencerStateMachine( 2212): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager( 1478): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
W/ResourcesManager( 1478): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 1478): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
E/Zygote  ( 8847): MountEmulatedStorage()
E/Zygote  ( 8847): v2
I/libpersona( 8847): KNOX_SDCARD checking this for 10019
I/libpersona( 8847): KNOX_SDCARD not a persona
I/ActivityManager(  846): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8847 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 8847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8847): TimaSignature is unavailable
D/ActivityThread( 8847): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetView( 1478): destroyHardwareResources():11941581
D/ResourcesManager( 8847): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  846): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  846): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Launcher( 1478): onRestart, Launcher: 254831523
D/Launcher( 1478): onStart, Launcher: 254831523
D/Launcher.HomeView( 1478): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2140): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2140): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  846): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  846): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/InputMethodManagerService(  846): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  846): Got RemoteException sending setActive(false) notification to pid 7428 uid 10367
W/ContextImpl(  846): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/KLMS-2.4.503: ( 8847): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/art     (  846): Explicit concurrent mark sweep GC freed 61936(6MB) AllocSpace objects, 205(3MB) LOS objects, 30% free, 36MB/52MB, paused 8.822ms total 295.111ms
D/ResourcesManager(  846): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/KLMS-2.4.503: ( 8847): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452021048786
I/KLMS-2.4.503: ( 8847): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8847): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
I/art     (  846): WaitForGcToComplete blocked for 211.111ms for cause Explicit
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
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SecContentProvider2(  846): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  846): mCursor = null
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Timeline(  846): Timeline: Activity_windows_visible id: ActivityRecord{1d0154ae u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1908384
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/EnterpriseDeviceManagerService(  846): Package has changed for user 0
D/EnterpriseDeviceManagerService(  846): Admin package name: com.google.android.gms
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/RegisteredServicesCache( 1458): empty dynamic service
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
E/Zygote  ( 8867): MountEmulatedStorage()
E/Zygote  ( 8867): v2
I/libpersona( 8867): KNOX_SDCARD checking this for 10104
I/libpersona( 8867): KNOX_SDCARD not a persona
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/ActivityManager(  846): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8867 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  846): Killing 7893:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1804s
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
I/SELinux ( 8867): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/SELinux ( 8867): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8867): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/libprocessgroup(  846): failed to open /acct/uid_10178/pid_7893/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8867): TimaSignature is unavailable
D/ActivityThread( 8867): Added TimaKeyStore provider
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 8867): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  846): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/RCPManagerService(  846): PackageReceiver onReceive()
I/HarmonyEASService(  846): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14451( 8867): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/KnoxMUMContainerPolicy(  846): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:14451( 8867): ELMEngine.ELMEngine( context ).
D/BackupManagerService(  846): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  846): Receieved: android.intent.action.PACKAGE_REMOVED
D/elm:14451( 8867): MDMBridge.setEnterpriseBridge()
V/EnterpriseBillingPolicy(  846): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  846): uID is 10367
V/EnterpriseBillingPolicy(  846): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  846): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  846): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  846): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  846): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  846): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  846): getBillingProfileForVpnEngine - end - null
I/art     (  846): Explicit concurrent mark sweep GC freed 13676(609KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 3.135ms total 310.229ms
D/elm:14451( 8867): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8867): ElmAgentService : onCreate()
D/elm:14451( 8867): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/elm:14451( 8867): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8867): MDMBridge.getInstance()
D/elm:14451( 8867): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8867): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8883): MountEmulatedStorage()
E/Zygote  ( 8883): v2
I/libpersona( 8883): KNOX_SDCARD checking this for 10017
I/libpersona( 8883): KNOX_SDCARD not a persona
I/ActivityManager(  846): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8883 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/TaskPersister(  846): removeObsoleteFile: deleting file=11_task.xml
I/SELinux ( 8883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 8867): ElmAgentService : onDestroy().
I/ActivityManager(  846): Killing 7558:com.google.android.music:main/u0a126 (adj 15): empty for 1802s
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/TimaKeyStoreProvider( 8883): TimaSignature is unavailable
D/ActivityThread( 8883): Added TimaKeyStore provider
D/ResourcesManager( 8883): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8883): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8883): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8883): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
E/Zygote  ( 8899): MountEmulatedStorage()
E/Zygote  ( 8899): v2
I/libpersona( 8899): KNOX_SDCARD checking this for 1000
I/libpersona( 8899): KNOX_SDCARD not a persona
I/ActivityManager(  846): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8899 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  846): Killing 4902:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1803s
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  846): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  846): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  846): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SELinux ( 8899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  846): failed to open /acct/uid_10126/pid_7558/cgroup.procs: No such file or directory
I/SELinux ( 8899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager(  846): delete codoeFile: 
D/PackageManager(  846): result of delete: 1{702735541}
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/AndroidRuntime( 8818): Shutting down VM
D/TimaKeyStoreProvider( 8899): TimaSignature is unavailable
D/ActivityThread( 8899): Added TimaKeyStore provider
W/libprocessgroup(  846): failed to open /acct/uid_10012/pid_4902/cgroup.procs: No such file or directory
D/ResourcesManager(  846): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager( 8899): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ResourcesManager(  846): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/PCWCLIENTTRACE_LOG( 8899): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8899): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8899): new DMDBOpenHelper instance
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/PCWCLIENTTRACE_PushUtil( 8899): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8899): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8899): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8899): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  846): checkUser: useridlist=null, currentuser=0
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
E/Zygote  ( 8914): MountEmulatedStorage()
E/Zygote  ( 8914): v2
I/libpersona( 8914): KNOX_SDCARD checking this for 10034
I/libpersona( 8914): KNOX_SDCARD not a persona
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  846): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8914 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  846): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/ActivityManager(  846): Killing 5171:com.sec.spp.push/u0a38 (adj 15): empty for 1802s
I/SELinux ( 8914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  846): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 8914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbSettingsManager(  846): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  846): onPackageRemoved : com.test.thalitest
D/TimaKeyStoreProvider( 8914): TimaSignature is unavailable
D/ActivityThread( 8914): Added TimaKeyStore provider
D/ResourcesManager( 8914): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/libprocessgroup(  846): failed to open /acct/uid_10038/pid_5171/cgroup.procs: No such file or directory
I/FeatureConfig( 8914): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 8914): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 8914): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8914): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 8914): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 8914): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8914): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 8914): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 8914): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8914): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8914): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 8914): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.

```
