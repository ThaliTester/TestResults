#### Test 50650278d6c551a_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7316): null auth token
I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
I/qtaguid ( 7316): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
I/qtaguid ( 7316): Untagging socket 34
W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
W/ApiaryClient( 7316): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4084563137336859861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
--------- beginning of system
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AndroidRuntime( 7388): 
D/AndroidRuntime( 7388): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7388): CheckJNI is OFF
D/AndroidRuntime( 7388): setted country_code = Germany
D/AndroidRuntime( 7388): setted countryiso_code = DE
D/AndroidRuntime( 7388): setted sales_code = DBT
D/AndroidRuntime( 7388): readGMSProperty: start
D/AndroidRuntime( 7388): readGMSProperty: already setted!!
D/AndroidRuntime( 7388): readGMSProperty: end
D/AndroidRuntime( 7388): addProductProperty: start
V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7316): null auth token
I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
I/qtaguid ( 7316): Untagging socket 34
W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
W/ApiaryClient( 7316): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4084563137336859861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/AffinityControl( 7388): AffinityControl: registerfunction enter
D/AndroidRuntime( 7388): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  894): inState():  stateMachine is null !!
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  894): mDVFSHelper.acquire()
D/FocusedStackFrame(  894): Set to : 0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  894): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7413 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7413): MountEmulatedStorage()
I/libpersona( 7413): KNOX_SDCARD checking this for 10367
E/Zygote  ( 7413): v2
I/libpersona( 7413): KNOX_SDCARD not a persona
I/SELinux ( 7413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SELinux ( 7413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7413): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7388): Shutting down VM
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/TimaKeyStoreProvider( 7413): TimaSignature is unavailable
D/ActivityThread( 7413): Added TimaKeyStore provider
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  894): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  894): Display changed displayId=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1494): destroyHardwareResources():539533495
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2108): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1494): onTrimMemory. Level: 20
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7413): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SQLiteSecureOpenHelper( 3573): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3573): getDatabaseLocked(b,b,pwd)...
,W/ProcessCpuTracker(  894): Skipping unknown process pid 7388
,I/WebViewFactory( 7413): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7413): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7413): Loading: webviewchromium
,I/LibraryLoader( 7413): Time to load native libraries: 2 ms (timestamps 7143-7145)
I/LibraryLoader( 7413): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7413): Binding Chromium to main looper Looper (main, tid 1) {3d8cefdf}
,I/LibraryLoader( 7413): Expected native library version number "",actual native library version number ""
I/chromium( 7413): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7413): Initializing chromium process, renderers=0
,W/art     ( 7413): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7413): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7413): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7413): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7413): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7413): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7413): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7413): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7413): Remote Branch: 
I/Adreno-EGL( 7413): Local Patches: 
I/Adreno-EGL( 7413): Reconstruct Branch: 
,E/SMD     (  290): DCD ON
,W/chromium( 7413): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7413): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7413): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7413): onDetachedFromWindow called when already detached. Ignoring
E/BooksSync( 7316): Soft error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4084563137336859861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7316): Sync error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4084563137336859861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7316): Finished books sync
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  894): Activity pause timeout for ActivityRecord{2d879e4a u0 com.test.thalitest/.MainActivity t11}
,D/SystemWebViewEngine( 7413): CordovaWebView is running on device made by: samsung
,D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66920, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  894): Killing 6557:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/art     ( 7413): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7413): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6557/cgroup.procs: No such file or directory
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Activity( 7413): performCreate Call secproduct feature valuefalse
,D/Activity( 7413): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7413): Render dirty regions requested: true
,D/ActivityManager(  894): post active user change for 0
,D/KnoxTimeoutHandler(  894): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  894): handleActiveUserChange for user 0
,I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/OpenGLRenderer( 7413): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7413): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7413): Enabling debug mode 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/ActivityManager(  894): mDVFSHelper.release()
I/Timeline(  894): Timeline: Activity_windows_visible id: ActivityRecord{2d879e4a u0 com.test.thalitest/.MainActivity t11} time:97750
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/IInputConnectionWrapper( 7413): showStatusIcon on inactive InputConnection
I/Timeline( 7413): Timeline: Activity_idle id: android.os.BinderProxy@3792032e time:97755
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/chromium( 7413): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7413): 
,D/JsMessageQueue( 7413): Set native->JS mode to OnlineEventsBridgeMode
,I/GAV2    ( 7316): Thread[GAThread,5,main]: No campaign data found.
,D/jxcore_app_log( 7413): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1359593600
,D/JX-Cordova( 7413): jxcore cordova android initializing
,W/jxcore-log( 7413): Initializing JXcore engine
,W/jxcore-log( 7413): JXcore engine is ready
,W/jxcore-log( 7413): Starting JXcore engine
,E/auditd  ( 2239): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  894): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  894): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7510): MountEmulatedStorage()
I/libpersona( 7510): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7510): v2
I/libpersona( 7510): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7510 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7510): TimaSignature is unavailable
,D/ActivityThread( 7510): Added TimaKeyStore provider
,W/jxcore-log( 7413): Platform android
W/jxcore-log( 7413): 
W/jxcore-log( 7413): Process ARCH arm
W/jxcore-log( 7413): 
,D/ResourcesManager( 7510): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7510):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7510):  SeDenialReceiver : File path = null
,I/ActivityManager(  894): Killing 6591:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6591/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD ON
,I/jxcore-log( 7413): JXcore Cordova bridge is ready!
I/jxcore-log( 7413): 
W/jxcore-log( 7413): JXcore engine is started
,I/jxcore-log( 7413): Toggling radios to true
I/jxcore-log( 7413): 
,D/BluetoothAdapter( 7413): enable()
,D/BluetoothAdapter( 7413): enable(): BT is already enabled..!
,D/WifiService(  894): New client listening to asynchronous messages
,I/WifiManager( 7413): packageName : com.test.thalitest
,D/SecContentProvider(  894): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  894): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  894): mCursor = null
,D/WifiService(  894): setWifiEnabled: true pid=7413, uid=10367
,E/WifiService(  894): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  894): Permission Denial: getCurrentUser() from pid=7413, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  894): Failed getting userId using ActivityManagerNative
W/WifiService(  894): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7413, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  894): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  894): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  894): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  894): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  894): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  894): name = wifi_on
,I/WifiService(  894): disconnect: pid=7413, uid=10367
,I/jxcore-log( 7413): Radios toggled
I/jxcore-log( 7413): 
,I/wpa_supplicant( 1289): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7413): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7413): 
,I/jxcore-log( 7413): Perf Test app loaded loaded
I/jxcore-log( 7413): 
,I/jxcore-log( 7413): check test folder
I/jxcore-log( 7413): 
,I/jxcore-log( 7413): found test : ./testFindPeers.js
I/jxcore-log( 7413): 
,I/wpa_supplicant( 1289): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1289): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1289): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1289): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  894): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1289): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1289): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1289): Disconnected - do not scan
I/wpa_supplicant( 1289): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  894): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 7413): found test : ./testSendData.js
I/jxcore-log( 7413): 
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ what=143375 }
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  894): waitForAlarm result :4
,D/CommandListener(  285): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,V/NativeCrypto( 1648): Read error: ssl=0xaf63be00: I/O error during system call, Connection timed out
,E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  894): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1289): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1289): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1289): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1289): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1289): First Scan Start
,I/wpa_supplicant( 1289): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  894): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  894): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,V/NativeCrypto( 1648): SSL shutdown failed: ssl=0xaf63be00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ what=143375 }
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=-3ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  285): Clearing all IP addresses on wlan0
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  894): Not allowed due to - mEnabled false
,D/ConnectivityService(  894): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Disconnected - quitting
,I/Hs20UtilService( 1295): Starting #6
D/ConnectivityService(  894): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Hs20UtilService( 1295): Message received 5007
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  894): updateConfiguredNetworkExpiration - currTime: 1449754792440
D/WifiStateMachine(  894): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/CSLegacyTypeTracker(  894): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
D/CSLegacyTypeTracker(  894): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1472): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiStateMachine(  894): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  894): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  894): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  894): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,V/NetworkStats(  894): updateIfacesLocked()
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
V/NetworkStats(  894): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  894): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/ConnectivityService(  894): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
V/NetworkStats(  894): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,V/NetworkStats(  894): performPollLocked() took 7ms
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,I/Hs20UtilService( 1295): Starting #7
,I/Hs20UtilService( 1295): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/chromium( 7413): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,I/chromium( 7413): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6636): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6636): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6636): [1] 5.onFinished: Scheduling replication attempt 2.
,W/ProcessCpuTracker(  894): Skipping unknown process pid 7545
,W/ProcessCpuTracker(  894): Skipping unknown process pid 7548
,W/ProcessCpuTracker(  894): Skipping unknown process pid 7550
W/ProcessCpuTracker(  894): Skipping unknown process pid 7551
W/ProcessCpuTracker(  894): Skipping unknown process pid 7555
W/ProcessCpuTracker(  894): Skipping unknown process pid 7572
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2108): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,I/ApplicationPolicy(  894): updateDataUsageMap
,I/PCWCLIENTTRACE_PushUtil( 6747): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6747): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6747): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6747): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6747): noConnectivity : true
,I/CLocInfoService(  894): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  894): CLoinfo wifi false
,W/SLocation(  894): No Active Data Connection
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7129): [#DCM#] [DCM_Performance] onReceive completed in time  4287 microsec. 
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5349): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7129): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7129): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7129): [#DCM#] setIsConnectedForExtractors 
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3838): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/Zygote  ( 7580): MountEmulatedStorage()
E/Zygote  ( 7580): v2
I/libpersona( 7580): KNOX_SDCARD checking this for 10002
I/libpersona( 7580): KNOX_SDCARD not a persona
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3838): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/ActivityManager(  894): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7580 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/art     (  320): Explicit concurrent mark sweep GC freed 8742(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 13.874ms
E/SELinux ( 7580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 396us total 8.941ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 241us total 8.171ms
,D/TimaKeyStoreProvider( 7580): TimaSignature is unavailable
,D/ActivityThread( 7580): Added TimaKeyStore provider
,D/ResourcesManager( 7580): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  894): Killing 6702:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7607): MountEmulatedStorage()
E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 1000
I/libpersona( 7607): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  894): failed to open /acct/uid_10015/pid_6702/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
,D/ActivityThread( 7607): Added TimaKeyStore provider
,D/ResourcesManager( 7607): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7607): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7607): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7607): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7607): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7607): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7607): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7627): MountEmulatedStorage()
,E/Zygote  ( 7627): v2
I/libpersona( 7627): KNOX_SDCARD checking this for 10011
I/libpersona( 7627): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7627 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7627): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7627): TimaSignature is unavailable
,D/ActivityThread( 7627): Added TimaKeyStore provider
,D/ResourcesManager( 7627): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1289): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1289): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1289): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1289): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1289): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  894): [1,449,754,793,475 ms] noteScanEnd no scan source
,I/ActivityManager(  894): Killing 6728:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/WifiStateMachine(  894): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@19f0dec1 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  894): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info0x
,I/CLocInfoService(  894): External Intent Received android.net.wifi.SCAN_RESULTS
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,I/FOTA_Client( 7627): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7627): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7627): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7627): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7627): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7649): MountEmulatedStorage()
E/Zygote  ( 7649): v2
,I/libpersona( 7649): KNOX_SDCARD checking this for 10019
I/libpersona( 7649): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7649 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6509:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  894): failed to open /acct/uid_10016/pid_6728/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1289): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1289): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1289): Associated with C0.AA.48
E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,I/wpa_supplicant( 1289): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1289): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  894): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  894): mCursor = null
,D/TimaKeyStoreProvider( 7649): TimaSignature is unavailable
,D/ActivityThread( 7649): Added TimaKeyStore provider
,I/wpa_supplicant( 1289): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1289): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1289): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  894): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1289): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1289): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1289): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1289): Blacklist: Clear (temp) 
I/wpa_supplicant( 1289): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  894): Network connection established
,D/WifiNative-HAL(  894): callSECApiVoid - ID [50]
,E/WifiStateMachine(  894): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,W/libprocessgroup(  894): failed to open /acct/uid_10034/pid_6509/cgroup.procs: No such file or directory
,E/WifiStateMachine(  894): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  894): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  894): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  894): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  894): Got NetworkAgent Messenger
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894): NetworkAgent connected
E/WifiStateMachine(  894): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7649): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/WifiStateMachine(  894): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  894): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  894): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  285): Setting iface cfg
,E/WifiStateMachine(  894): Start Dhcp Watchdog 2
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  894): mCursor = null
,I/KLMS-2.4.503: ( 7649): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7649): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449754793609
,I/KLMS-2.4.503: ( 7649): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7649): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7649): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  894): Killing 4799:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7667): MountEmulatedStorage()
I/libpersona( 7667): KNOX_SDCARD checking this for 10037
E/Zygote  ( 7667): v2
I/libpersona( 7667): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7667 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7667): TimaSignature is unavailable
,D/ActivityThread( 7667): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10035/pid_4799/cgroup.procs: No such file or directory
,D/ResourcesManager( 7667): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend false
,I/SO_AGENT( 7667): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/WifiP2pService(  894): InactiveState{ what=143375 }
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5243): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6788): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6788): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6788): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6788): [SLFUCHKMGR] constructor called
,I/SA      ( 6788): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6788): [OR] == isSIMCardReady false ==
,I/SA      ( 6788): [SCU] == networkStateCheck == false
I/SA      ( 6788): [OR] onReceive END
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/SPPClientService( 5243): [[SystemStateMonitorService]] No Active Internet
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7684): MountEmulatedStorage()
,E/Zygote  ( 7684): v2
I/libpersona( 7684): KNOX_SDCARD checking this for 10071
I/libpersona( 7684): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7684 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  894): Killing 6052:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,E/SELinux ( 7684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7684): TimaSignature is unavailable
,D/ActivityThread( 7684): Added TimaKeyStore provider
,D/ResourcesManager( 7684): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7684): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SMD     (  290): DCD ON
,W/libprocessgroup(  894): failed to open /acct/uid_10042/pid_6052/cgroup.procs: No such file or directory
,D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7684): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7684): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7684): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7684): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7684): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  894): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 10071
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7684): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7684): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7684): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7684): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7684): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7684): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1343): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Watchdog(  894): !@Sync 3
,E/Zygote  ( 7701): MountEmulatedStorage()
E/Zygote  ( 7701): v2
I/libpersona( 7701): KNOX_SDCARD checking this for 1000
I/libpersona( 7701): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7701 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 5704:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7709): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7709): version 5.5.6 starting
,E/dhcpcd  ( 7709): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7701): TimaSignature is unavailable
,D/ActivityThread( 7701): Added TimaKeyStore provider
,D/CountryDetector(  894): No listener is left
,D/ResourcesManager( 7701): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7701): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7701): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7701): premStatus:2
,W/libprocessgroup(  894): failed to open /acct/uid_10050/pid_5704/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7701): isEulaShown : false
I/KnoxUsageLogPro( 7701): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7709): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7709): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7709): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7709): bssid match
,I/dhcpcd  ( 7709): wlan0: rebinding lease of 192.168.1.135
,E/Zygote  ( 7723): MountEmulatedStorage()
E/Zygote  ( 7723): v2
I/libpersona( 7723): KNOX_SDCARD checking this for 10088
I/libpersona( 7723): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7723 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6809:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7723): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7723): TimaSignature is unavailable
,D/ActivityThread( 7723): Added TimaKeyStore provider
,D/ResourcesManager( 7723): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  894): failed to open /acct/uid_10051/pid_6809/cgroup.procs: No such file or directory
,I/ActivityManager(  894): Killing 6826:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,V/AlarmManager(  894): waitForAlarm result :4
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5512): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7739): MountEmulatedStorage()
,E/Zygote  ( 7739): v2
I/libpersona( 7739): KNOX_SDCARD checking this for 10128
I/libpersona( 7739): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7739 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  894): failed to open /acct/uid_10058/pid_6826/cgroup.procs: No such file or directory
,I/SELinux ( 7739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7739): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7739): TimaSignature is unavailable
,D/ActivityThread( 7739): Added TimaKeyStore provider
,D/ResourcesManager( 7739): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  894): [PWL] Off : 30s ago
I/PowerManagerService(  894): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  894): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=894, ws=null) (elapsedTime=1819)
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=894, ws=WorkSource{10012}) (elapsedTime=130)
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7739): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7739): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7739): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7739): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/SSRM:m  (  894): SIOP:: AP = 390, PST = 431, CUR = 300
,I/WebViewFactory( 7739): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7739): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7739): Loading: webviewchromium
,I/LibraryLoader( 7739): Time to load native libraries: 4 ms (timestamps 4002-4006)
,I/LibraryLoader( 7739): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7739): Binding Chromium to main looper Looper (main, tid 1) {207cc8b5}
,I/LibraryLoader( 7739): Expected native library version number "",actual native library version number ""
,I/chromium( 7739): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7739): Initializing chromium process, renderers=0
,W/art     ( 7739): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7739): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7739): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7739): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7739): Requires BLUETOOTH permission
,I/Adreno-EGL( 7739): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7739): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7739): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7739): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7739): Remote Branch: 
I/Adreno-EGL( 7739): Local Patches: 
I/Adreno-EGL( 7739): Reconstruct Branch: 
,I/NSApplication( 7739): Starting up...
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7797): MountEmulatedStorage()
E/Zygote  ( 7797): v2
I/libpersona( 7797): KNOX_SDCARD checking this for 10138
I/libpersona( 7797): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7797 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6258:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7797): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6258/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7797): TimaSignature is unavailable
,D/ActivityThread( 7797): Added TimaKeyStore provider
,D/ResourcesManager( 7797): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7797): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7797): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7797): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7797): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7797): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7812): MountEmulatedStorage()
,E/Zygote  ( 7812): v2
I/libpersona( 7812): KNOX_SDCARD checking this for 10163
I/libpersona( 7812): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7812 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6848:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,I/SELinux ( 7812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7812): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7812): TimaSignature is unavailable
,D/ActivityThread( 7812): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10098/pid_6848/cgroup.procs: No such file or directory
,D/ResourcesManager( 7812): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7812): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7812): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7812): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7812): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,I/ActivityManager(  894): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7835 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,E/Zygote  ( 7835): MountEmulatedStorage()
E/Zygote  ( 7835): v2
I/libpersona( 7835): KNOX_SDCARD checking this for 10078
,I/libpersona( 7835): KNOX_SDCARD not a persona
,I/SELinux ( 7835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7835): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  320): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 13.286ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 9.684ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 7.565ms
,D/TimaKeyStoreProvider( 7835): TimaSignature is unavailable
,D/ActivityThread( 7835): Added TimaKeyStore provider
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/ResourcesManager( 7835): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,D/BadgeProvider( 7835): onCreate
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
D/BadgeProvider( 7835): DatabaseHelper
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,I/ActivityManager(  894): Killing 6898:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7510): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7510): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7510): StateMachine : Current State = 1
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,I/dhcpcd  ( 7709): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7812): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/dhcpcd  ( 7709): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,W/libprocessgroup(  894): failed to open /acct/uid_10033/pid_6898/cgroup.procs: No such file or directory
,I/art     (  894): Explicit concurrent mark sweep GC freed 58060(3MB) AllocSpace objects, 9(274KB) LOS objects, 30% free, 36MB/52MB, paused 1.494ms total 102.354ms
,D/SecurityLogAgent( 7510): StateMachine : Changed Current State = 1
,I/ActivityManager(  894): Killing 6873:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): NO active network... no services...
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): last run: 1449746146708 -- System.currentTimeMillis()-last_run: 8648413
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip last_72_check
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7835): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/Zygote  ( 7869): MountEmulatedStorage()
I/libpersona( 7869): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7869): v2
I/libpersona( 7869): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7869 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7869): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7835): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7835): sendNotify, [notify] : null
D/BadgeProvider( 7835): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7835): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7835): update, [UpdateCount] : 1
,D/Launcher.Model( 1494): reloadBadges entered.
,D/TimaKeyStoreProvider( 7869): TimaSignature is unavailable
,D/ActivityThread( 7869): Added TimaKeyStore provider
,W/libprocessgroup(  894): failed to open /acct/uid_10099/pid_6873/cgroup.procs: No such file or directory
,W/ActivityManager(  894): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 7869): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  894): Killing 6940:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/iu.Environment( 2349): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2349): num queued entries: 0
,I/iu.UploadsManager( 2349): num updated entries: 0
,I/iu.SyncManager( 2349): NEXT; no task
,D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Hs20UtilService( 1295): Starting #8
I/Hs20UtilService( 1295): Message received 5007
,W/libprocessgroup(  894): failed to open /acct/uid_10020/pid_6940/cgroup.procs: No such file or directory
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine(  894): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  894): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ what=143375 }
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  894): WifiStateMachine DHCP successful
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  894): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  894): Not connected state, yet.
E/WifiStateMachine(  894): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiStateMachine(  894): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  894): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  894): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  894): callSECApiInt - ID [210]
,E/WifiStateMachine(  894): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  894): updateNetworkInfo()
,D/ConnectivityService(  894): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  894): Adding iface wlan0 to network 503
I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
D/WifiWatchdogStateMachine(  894): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/Hs20UtilService( 1295): Starting #9
I/Hs20UtilService( 1295): Message received 5007
E/WifiStateMachine(  894): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  894): Now, connected state.
E/WifiStateMachine(  894): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  894): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  894): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  894): mBoosterFLAG : 0
I/WifiTrafficPoller(  894): current booster mode : FullMode
D/WifiNative-HAL(  894): callSECApiVoid - ID [212]
D/ConnectivityService(  894): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/CLocInfoService(  894): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  894): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  894): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService(  894): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
I/WifiStateMachine(  894): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
E/ConnectivityService(  894): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  894): updateSourceRoutes : add source routing for type : 1
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/ConnectivityService(  894): updateSourceRoutes : add src route for:192.168.1.135
V/        (  285): QcRouteController
,V/        (  285): QcRouteController
I/Hs20UtilService( 1295): Starting #10
I/Hs20UtilService( 1295): Message received 5007
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/        (  285): QcRouteController
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
V/        (  285): QcRouteController
I/Hs20UtilService( 1295): Starting #11
I/Hs20UtilService( 1295): Message received 5007
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
I/WifiStateMachine(  894): callSECApi what=220
D/WifiStateMachine(  894): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  894): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): calling update connectivity
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): ignoring duplicate network state non-change
D/ConnectivityService(  894): ignoring duplicate network state non-change
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): currentScore = 0, newScore = 60
D/ConnectivityService(  894):    accepting network in place of null
D/ConnectivityService(  894): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1472): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
,E/CSLegacyTypeTracker(  894): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  894): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/PowerManagerService(  894): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/ConnectivityService(  894): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/LockPatternUtilsCache( 1169): value : false
D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/ConnectivityService(  894): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats(  894): updateIfacesLocked()
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/NetworkStats(  894): performPollLocked(flags=0x1)
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
D/EntConnectivity(  894): Not allowed due to - mEnabled false
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
V/NetworkStats(  894): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,V/NetworkStats(  894): performPollLocked() took 5ms
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
,D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  894): calling update connectivity
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/NtpTrustedTime(  894): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  894): MasterInitialState.processMessage what=3
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  894): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  894): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,I/CLocInfoService(  894): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  894): CLocinfo wifi true 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2272): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2108): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SystemBroadcastReceiver( 7129): [#DCM#] [DCM_Performance] onReceive completed in time  566 microsec. 
,I/SystemBroadcastReceiver( 7129): [#DCM#] Calling notifyListeners. 
I/DCMController( 7129): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7129): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5349): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 6747): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6747): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6747): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6747): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3838): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3838): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7129): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7129): [#DCM#] onCreate FrameworkService 
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,I/FrameworkService( 7129): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7129): [#DCM#] getSuccessState = true
I/FrameworkService( 7129): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7129): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/DIAGMON_AGENT( 7607): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7607): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SystemUtils( 7129): [#DCM#] LM: false,AM:701562880
,I/DCMThreadPoolExecutor( 7129): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7129): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@299b93de is submitted
I/FrameworkService( 7129): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 25647 mirosec. 
,I/FOTA_Client( 7627): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7627): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7627): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
I/FOTA_Client( 7627): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7627): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7649): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7649): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449754796363
,I/KLMS-2.4.503: ( 7649): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7649): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/KLMS-2.4.503: ( 7649): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7649): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7649): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7667): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5243): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6788): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6788): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6788): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6788): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6788): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6788): [SCU] == networkStateCheck == true
,I/SA      ( 6788): [DM] getCountryCodeFromCSC : DE
,I/SA      ( 6788): isChinaCountryCode : false
I/SA      ( 6788): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6788): [OR] == networkStateCheck true ==
,I/SA      ( 6788): [OR] GetMyCountryZoneTask
,I/SA      ( 6788): [OR] onReceive END
,I/SA      ( 6788): [SRS] prepareGetMyCountryZone
,I/SA      ( 6788): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6788): [SSP] query invoked
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6788): [TPMU] GetMccFromDB : null
I/SA      ( 6788): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6788): [TPM] isNoProxy(default) : true
,D/accuweather( 7684): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7684): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7701): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7701): premStatus:2
,I/KnoxUsageLogPro( 7701): isEulaShown : false
,I/KnoxUsageLogPro( 7701): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6788): fail readDirectory() errno=2
,D/Headlines( 5512): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5512): getCountryCode(): countryCode = DE
,D/Headlines( 5512): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5512): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5512): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5512): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5512): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7797): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7797): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7797): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7510): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7510): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 7510): StateMachine : Current State = 1
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7510): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
E/SMD     (  290): DCD ON
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): last run: 1449746146708 -- System.currentTimeMillis()-last_run: 8650093
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5616): ... skip last_72_check
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2349): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2349): num queued entries: 0
,I/iu.UploadsManager( 2349): num updated entries: 0
,I/iu.SyncManager( 2349): NEXT; no task
,D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2349): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7107): notifyNetworkActivated
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
,D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,W/ContextImpl( 7107): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  894): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2349): [AccountUtils] Account not ready
W/Kids    ( 2349): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2349): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2349): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2349): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2349): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2349): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/GCM     ( 1648): Connected
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1648): Message class com.google.f.a.a.p
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7107): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7107): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7107): exit::IDLE
D/InitializeManagerStateMachine( 7107): entry::NETWORK_CHECK
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7107): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7107): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7107): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7107): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7107): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7107): entry::SUCCESS
D/hcjo    ( 7107): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/jxcore-log( 7413): BLE supported!!
I/jxcore-log( 7413): 
,D/hcjo    ( 7107): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7107): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7107): exit::SUCCESS
D/InitializeManagerStateMachine( 7107): entry::IDLE
,I/SA      ( 6788): [RC New] Execute method=[GET] start
,I/SA      ( 6788): [RC New] Security=[true]
,I/System.out( 6788): Thread-1100(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6788): Thread-1100(ApacheHTTPLog):isShipBuild true
,I/System.out( 6788): Thread-1100(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/dhcpcd  ( 7709): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7709): wlan0: sendmsg: Cannot assign requested address
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/WifiStateMachine(  894): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  894): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
E/WifiStateMachine(  894): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  894): identical MTU - not setting
,D/ConnectivityService(  894): updateSourceRoutes : add source routing for type : 1
D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/ConnectivityService(  894): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,W/NetworkManagementService(  894): route cmd failed: 
W/NetworkManagementService(  894): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  894): '
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  894): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  894): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  894): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  894): calling update connectivity
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,I/WifiStateMachine(  894): REQUEST_POWER_SAVE_ON
,I/SA      ( 6788): [RC New] [v2liruge] api execute + 873
,I/SA      ( 6788): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6788): AsyncTask #1 calls detatch()
,I/SA      ( 6788): [ODM] saveOpenData( GEO_IP, PL )
,E/WifiStateMachine(  894): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 6788): [OCP] update openData : PL
,I/SA      ( 6788): [TPMU] getNetworkMcc : 
,I/SA      ( 6788): [SCU] saveMccToPreferece Start
,I/SA      ( 6788): [SCU] RegionMCC : 260
I/SA      ( 6788): [SSP] query invoked
,I/SA      ( 6788): [TPMU] GetMccFromDB : null
,I/SA      ( 6788): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6788): [SCU] saveMccToPreferece End
,I/SA      ( 6788): [RC New] executeRequest [v2liruge] end. 977
I/SA      ( 6788): [RC New] Execute end
,I/SA      ( 6788): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6788): [OR] GetMyCountryZoneTask Success
,I/SurfaceFlinger(  249): id=15 Removed Toast (8/9)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  894): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 894) eventTime = 108544
,D/PowerManagerService(  894): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894 (0x0)
,D/PowerManagerService(  894): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=894, ws=WorkSource{10059}) (elapsedTime=3530)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/GAV4    ( 7739): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6747): mConnectivityHandler : connected
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6747): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6747): ================================================
,I/CSTORAGE( 6747):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6747): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6747): [GetString-S]
,E/art     ( 6747): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6747): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6747): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6747): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6747): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6747): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6747): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7709): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:m  (  894): SIOP:: AP = 360, PST = 423, CUR = 300
,D/X       (  894): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ContentApp( 1222):  LEVEL : 0
,I/SystemBroadcastReceiver( 7129): [#DCM#] [DCM_Performance] onReceive completed in time  10053 microsec. 
,E/TranscodeReceiver( 7191): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7191):  SIOP_LEVEL: 0
,I/SystemBroadcastReceiver( 7129): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7129): [#DCM#] onReceive action = EVENT_SIOP
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/FactoryTest( 6470): Not factory mode
,D/FactoryTest( 6470): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6470): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6470): still no open session command from host, so toast
,W/ContextImpl( 6470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6470): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6470): Timeline: Activity_launch_request id:com.android.settings time:114889
,E/PersonaManagerService(  894): inState():  stateMachine is null !!
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  894): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6470): started activity for popup
,I/SQLiteSecureOpenHelper( 3573): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3573): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6470): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6470): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6470): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6470): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  894): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@29e35cc3 attribute=null, token = android.os.BinderProxy@31aea923
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6470): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6470): dev.kiessupport is : TRUE
,D/Activity( 6470): performCreate Call secproduct feature valuefalse
D/Activity( 6470): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  894): post active user change for 0
,D/KnoxTimeoutHandler(  894): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  894): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7413): Timeline: Activity_idle id: android.os.BinderProxy@3792032e time:115361
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/SMD     (  290): DCD ON
,I/dhcpcd  ( 7709): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7709): wlan0: no IPv6 Routers available
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7107): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7107): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7107): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7107): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7107): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7107): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7107): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7107): entry::IDLE
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ActivityManager(  894): mDVFSHelper.release()
,E/SMD     (  290): DCD ON
,I/ActivityManager(  894): Waited long enough for: ServiceRecord{1c852936 u0 com.samsung.dcm/.framework.FrameworkService}
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6636): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6636): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6636): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/PowerManagerService(  894): [PWL] Off : 50s ago
,D/SSRM:m  (  894): SIOP:: AP = 340, PST = 410, CUR = 300
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,E/SMD     (  290): DCD ON
,E/Watchdog(  894): !@Sync 4
,D/SSRM:m  (  894): SIOP:: AP = 330, PST = 395, CUR = 300
,D/X       (  894): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1222):  LEVEL : -1
,I/SystemBroadcastReceiver( 7129): [#DCM#] [DCM_Performance] onReceive completed in time  774 microsec. 
,E/TranscodeReceiver( 7191): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7191):  SIOP_LEVEL: -1
,I/SystemBroadcastReceiver( 7129): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7129): [#DCM#] onReceive action = EVENT_SIOP
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  894): waitForAlarm result :4
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 1648): Explicit concurrent mark sweep GC freed 31519(1908KB) AllocSpace objects, 20(1620KB) LOS objects, 39% free, 17MB/29MB, paused 836us total 103.995ms
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6636): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6636): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6636): [1] 5.onFinished: Scheduling replication attempt 4.
,D/SSRM:m  (  894): SIOP:: AP = 320, PST = 378, CUR = 300
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 75s ago
,E/SMD     (  290): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  894): SIOP:: AP = 320, PST = 365, CUR = 300
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1648): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6606): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at kff.l(PG:132)
E/HttpOperation( 6606): 	at dsf.a(PG:807)
E/HttpOperation( 6606): 	at fhk.a(PG:1126)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 8 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 10 more
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
,D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6606): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at kff.l(PG:132)
E/HttpOperation( 6606): 	at ieo.a(PG:43)
E/HttpOperation( 6606): 	at iep.a(PG:93)
E/HttpOperation( 6606): 	at fhn.a(PG:59)
E/HttpOperation( 6606): 	at lex.a(PG:85)
E/HttpOperation( 6606): 	at lex.b(PG:132)
E/HttpOperation( 6606): 	at fhk.a(PG:1146)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 12 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 14 more
,E/ExperimentLoader( 6606): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6606): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6606): 	at kfv.a(PG:65)
E/ExperimentLoader( 6606): 	at kff.u(PG:385)
E/ExperimentLoader( 6606): 	at kfb.a(PG:29)
E/ExperimentLoader( 6606): 	at kff.l(PG:132)
E/ExperimentLoader( 6606): 	at ieo.a(PG:43)
E/ExperimentLoader( 6606): 	at iep.a(PG:93)
E/ExperimentLoader( 6606): 	at fhn.a(PG:59)
E/ExperimentLoader( 6606): 	at lex.a(PG:85)
E/ExperimentLoader( 6606): 	at lex.b(PG:132)
E/ExperimentLoader( 6606): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6606): 	at fhk.a(PG:908)
E/ExperimentLoader( 6606): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6606): 	at ihi.a(PG:22)
E/ExperimentLoader( 6606): 	at kft.a(PG:91)
E/ExperimentLoader( 6606): 	at kfv.a(PG:62)
E/ExperimentLoader( 6606): 	... 12 more
E/ExperimentLoader( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6606): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6606): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6606): 	at ihi.a(PG:19)
E/ExperimentLoader( 6606): 	... 14 more
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
,D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6606): [getaccountstatus] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at ixd.a(PG:248)
E/HttpOperation( 6606): 	at ixd.b(PG:206)
E/HttpOperation( 6606): 	at ixd.a(PG:175)
E/HttpOperation( 6606): 	at fig.a(PG:78)
E/HttpOperation( 6606): 	at lex.a(PG:85)
E/HttpOperation( 6606): 	at lex.b(PG:132)
E/HttpOperation( 6606): 	at fhk.a(PG:1146)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 12 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 14 more
,E/EsSyncAdapterService( 6606): Sync failure
E/EsSyncAdapterService( 6606): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6606): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6606): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6606): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6606): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6606): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6606): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6606): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6606): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6606): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6606): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6606): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6606): 	... 10 more
E/EsSyncAdapterService( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6606): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6606): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6606): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6606): 	... 12 more
E/EsSyncAdapterService( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6606): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6606): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6606): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6606): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 156375, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  894): mCursor = null
,E/SMD     (  290): DCD ON
,E/SQLiteLog( 1648): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,E/Watchdog(  894): !@Sync 5
,D/SSRM:m  (  894): SIOP:: AP = 310, PST = 354, CUR = 300
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 310, PST = 343, CUR = 300
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD ON
,I/art     (  894): Explicit concurrent mark sweep GC freed 64549(3MB) AllocSpace objects, 30(740KB) LOS objects, 30% free, 36MB/52MB, paused 1.868ms total 166.531ms
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  894): [PWL] Off : 105s ago
,I/PowerManagerService(  894): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  894): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1648, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=147)
,I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1648, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=72)
,I/VacuumService( 1648): Vacuum at: now=1449754869312 tag=VacuumService
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1648): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
,D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/Uploader( 1648): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1648): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1648): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1648): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1648): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1648): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1648): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1648): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1648): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1648): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1648): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1648): (HTTPLog)-Static: isShipBuild true
I/System.out( 1648): (HTTPLog)-Thread-197-793292055: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1648): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1648): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6636): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6636): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6636): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1648): No account for auth token provided
,I/qtaguid ( 1648): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,W/Uploader( 1648): No account for auth token provided
,I/qtaguid ( 1648): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,W/Uploader( 1648): No account for auth token provided
,I/qtaguid ( 1648): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,W/Uploader( 1648): No account for auth token provided
,I/qtaguid ( 1648): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,W/Uploader( 1648): No account for auth token provided
,I/qtaguid ( 1648): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,W/Uploader( 1648):  no longer exists, so no auth token.
,I/qtaguid ( 1648): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1648, getuid(): 10012
,E/SQLiteLog( 1648): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,D/SSRM:m  (  894): SIOP:: AP = 310, PST = 335, CUR = 300
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7316): Starting books sync, d
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1648): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1679550064123610068&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1679550064123610068&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1679550064123610068&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,E/BooksSync( 7316): Soft error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1679550064123610068&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7316): Sync error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=1679550064123610068&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7316): Finished books sync
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159550, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  894): mCursor = null
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6606): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at kff.l(PG:132)
E/HttpOperation( 6606): 	at dsf.a(PG:807)
E/HttpOperation( 6606): 	at fhk.a(PG:1126)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 8 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 10 more
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6606): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at kff.l(PG:132)
E/HttpOperation( 6606): 	at ieo.a(PG:43)
E/HttpOperation( 6606): 	at iep.a(PG:93)
E/HttpOperation( 6606): 	at fhn.a(PG:59)
E/HttpOperation( 6606): 	at lex.a(PG:85)
E/HttpOperation( 6606): 	at lex.b(PG:132)
E/HttpOperation( 6606): 	at fhk.a(PG:1146)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 12 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 14 more
,E/ExperimentLoader( 6606): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6606): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6606): 	at kfv.a(PG:65)
E/ExperimentLoader( 6606): 	at kff.u(PG:385)
E/ExperimentLoader( 6606): 	at kfb.a(PG:29)
E/ExperimentLoader( 6606): 	at kff.l(PG:132)
E/ExperimentLoader( 6606): 	at ieo.a(PG:43)
E/ExperimentLoader( 6606): 	at iep.a(PG:93)
E/ExperimentLoader( 6606): 	at fhn.a(PG:59)
E/ExperimentLoader( 6606): 	at lex.a(PG:85)
E/ExperimentLoader( 6606): 	at lex.b(PG:132)
E/ExperimentLoader( 6606): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6606): 	at fhk.a(PG:908)
E/ExperimentLoader( 6606): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6606): 	at ihi.a(PG:22)
E/ExperimentLoader( 6606): 	at kft.a(PG:91)
E/ExperimentLoader( 6606): 	at kfv.a(PG:62)
E/ExperimentLoader( 6606): 	... 12 more
E/ExperimentLoader( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6606): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6606): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6606): 	at ihi.a(PG:19)
E/ExperimentLoader( 6606): 	... 14 more
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6606): [getaccountstatus] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at ixd.a(PG:248)
E/HttpOperation( 6606): 	at ixd.b(PG:206)
E/HttpOperation( 6606): 	at ixd.a(PG:175)
E/HttpOperation( 6606): 	at fig.a(PG:78)
E/HttpOperation( 6606): 	at lex.a(PG:85)
E/HttpOperation( 6606): 	at lex.b(PG:132)
E/HttpOperation( 6606): 	at fhk.a(PG:1146)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 12 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 14 more
E/EsSyncAdapterService( 6606): Sync failure
E/EsSyncAdapterService( 6606): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6606): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6606): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6606): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6606): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6606): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6606): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6606): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6606): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6606): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6606): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6606): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6606): 	... 10 more
E/EsSyncAdapterService( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6606): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6606): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6606): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6606): 	... 12 more
E/EsSyncAdapterService( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6606): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6606): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6606): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6606): 	... 14 more
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 188276, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,E/SQLiteLog( 1648): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,E/Watchdog(  894): !@Sync 6
,D/SSRM:m  (  894): SIOP:: AP = 310, PST = 330, CUR = 300
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :4
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6636): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6636): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6636): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 310, PST = 322, CUR = 300
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  894): [PWL] Off : 140s ago
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 316, CUR = 300
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,E/Watchdog(  894): !@Sync 7
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 312, CUR = 300
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 309, CUR = 300
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 307, CUR = 300
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7316): Starting books sync, d
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1648): Explicit concurrent mark sweep GC freed 49393(2MB) AllocSpace objects, 63(4MB) LOS objects, 40% free, 18MB/30MB, paused 925us total 126.877ms
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1648): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
,D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SMD     (  290): DCD ON
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9151618993540151219&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...,
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9151618993540151219&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9151618993540151219&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/BooksSync( 7316): Soft error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9151618993540151219&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7316): Sync error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9151618993540151219&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7316): Finished books sync
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 223360, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  894): Explicit concurrent mark sweep GC freed 51752(2MB) AllocSpace objects, 36(1226KB) LOS objects, 30% free, 36MB/52MB, paused 1.847ms total 133.335ms
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD ON
,E/Watchdog(  894): !@Sync 8
,I/PowerManagerService(  894): [PWL] Off : 180s ago
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 305, CUR = 300
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  290): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 303, CUR = 300
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1648): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6606): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at kff.l(PG:132)
E/HttpOperation( 6606): 	at dsf.a(PG:807)
E/HttpOperation( 6606): 	at fhk.a(PG:1126)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 8 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 10 more
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  290): DCD ON
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6606): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at kff.l(PG:132)
E/HttpOperation( 6606): 	at ieo.a(PG:43)
E/HttpOperation( 6606): 	at iep.a(PG:93)
E/HttpOperation( 6606): 	at fhn.a(PG:59)
E/HttpOperation( 6606): 	at lex.a(PG:85)
E/HttpOperation( 6606): 	at lex.b(PG:132)
E/HttpOperation( 6606): 	at fhk.a(PG:1146)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 12 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 14 more
E/ExperimentLoader( 6606): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6606): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6606): 	at kfv.a(PG:65)
E/ExperimentLoader( 6606): 	at kff.u(PG:385)
E/ExperimentLoader( 6606): 	at kfb.a(PG:29)
E/ExperimentLoader( 6606): 	at kff.l(PG:132)
E/ExperimentLoader( 6606): 	at ieo.a(PG:43)
E/ExperimentLoader( 6606): 	at iep.a(PG:93)
E/ExperimentLoader( 6606): 	at fhn.a(PG:59)
E/ExperimentLoader( 6606): 	at lex.a(PG:85)
E/ExperimentLoader( 6606): 	at lex.b(PG:132)
E/ExperimentLoader( 6606): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6606): 	at fhk.a(PG:908)
E/ExperimentLoader( 6606): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6606): 	at ihi.a(PG:22)
E/ExperimentLoader( 6606): 	at kft.a(PG:91)
E/ExperimentLoader( 6606): 	at kfv.a(PG:62)
E/ExperimentLoader( 6606): 	... 12 more
E/ExperimentLoader( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6606): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6606): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6606): 	at ihi.a(PG:19)
E/ExperimentLoader( 6606): 	... 14 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6606): [getaccountstatus] Unexpected exception
E/HttpOperation( 6606): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6606): 	at kfv.a(PG:65)
E/HttpOperation( 6606): 	at kff.u(PG:385)
E/HttpOperation( 6606): 	at kfb.a(PG:29)
E/HttpOperation( 6606): 	at ixd.a(PG:248)
E/HttpOperation( 6606): 	at ixd.b(PG:206)
E/HttpOperation( 6606): 	at ixd.a(PG:175)
E/HttpOperation( 6606): 	at fig.a(PG:78)
E/HttpOperation( 6606): 	at lex.a(PG:85)
E/HttpOperation( 6606): 	at lex.b(PG:132)
E/HttpOperation( 6606): 	at fhk.a(PG:1146)
E/HttpOperation( 6606): 	at fhk.a(PG:908)
E/HttpOperation( 6606): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6606): 	at ihi.a(PG:22)
E/HttpOperation( 6606): 	at kft.a(PG:91)
E/HttpOperation( 6606): 	at kfv.a(PG:62)
E/HttpOperation( 6606): 	... 12 more
E/HttpOperation( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6606): 	at gde.c(Unknown Source)
E/HttpOperation( 6606): 	at gde.b(Unknown Source)
E/HttpOperation( 6606): 	at ihi.a(PG:19)
E/HttpOperation( 6606): 	... 14 more
E/EsSyncAdapterService( 6606): Sync failure
E/EsSyncAdapterService( 6606): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6606): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6606): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6606): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6606): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6606): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6606): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6606): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6606): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6606): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6606): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6606): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6606): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6606): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6606): 	... 10 more
E/EsSyncAdapterService( 6606): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6606): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6606): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6606): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6606): 	... 12 more
E/EsSyncAdapterService( 6606): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6606): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6606): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6606): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6606): 	... 14 more
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 253442, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,E/SQLiteLog( 1648): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/Watchdog(  894): !@Sync 9
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  290): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 225s ago
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 300, CUR = 300
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD ON
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,D/TimaService(  894): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  894): TimaServiceHandler.handleMessage what =1
,D/TimaService(  894): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  894): initializing...
,I/TLC_TIMA_PKM_initialize(  894): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  894): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  894): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  894): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  894): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  894): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  894): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  894): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  894): App is not loaded in QSEE
,D/QSEECOMAPI: (  894): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  894): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  894): Trustlet response is completed
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD ON,
,E/Watchdog(  894): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  290): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,E/SMD     (  290): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  894): waitForAlarm result :4
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 8234): MountEmulatedStorage()
,E/Zygote  ( 8234): v2
,I/libpersona( 8234): KNOX_SDCARD checking this for 10081
,I/libpersona( 8234): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8234 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8234): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8234): TimaSignature is unavailable
,D/ActivityThread( 8234): Added TimaKeyStore provider
,D/ResourcesManager( 8234): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,E/SMD     (  290): DCD ON
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7316): Starting books sync, d
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5028665894427791183&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1648): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5028665894427791183&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1648): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1648): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1648): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1648): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1648): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1648): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
,D/SecContentProvider2(  894): mCursor = null
,D/SecContentProvider2(  894): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1648): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1648): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1648): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1648): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1648): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7316): Authentication error
E/BooksAccountManager( 7316): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7316): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7316): null auth token
,I/qtaguid ( 7316): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7316, getuid(): 10082
,I/qtaguid ( 7316): Untagging socket 34
,W/ApiaryClient( 7316): Error response from books API: {
W/ApiaryClient( 7316):  "error": {
W/ApiaryClient( 7316):   "errors": [
W/ApiaryClient( 7316):    {
W/ApiaryClient( 7316):     "domain": "global",
W/ApiaryClient( 7316):     "reason": "required",
W/ApiaryClient( 7316):     "message": "Login Required",
W/ApiaryClient( 7316):     "locationType": "header",
W/ApiaryClient( 7316):     "location": "Authorization"
W/ApiaryClient( 7316):    }
W/ApiaryClient( 7316):   ],
W/ApiaryClient( 7316):   "code": 401,
W/ApiaryClient( 7316):   "message": "Login Required"
W/ApiaryClient( 7316):  }
W/ApiaryClient( 7316): }
,W/ApiaryClient( 7316): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5028665894427791183&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7316): Headers suppressed
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/BooksSync( 7316): Soft error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5028665894427791183&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7316): Sync error
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7316): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5028665894427791183&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7316): Headers suppressed
E/BooksSync( 7316): 
E/BooksSync( 7316): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7316): Finished books sync
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 316735, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  894): mCursor = null
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD ON
,E/Watchdog(  894): !@Sync 11
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  894): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  894):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3276): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3276): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  894): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  290): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/PowerManagerService(  894): [PWL] Off : 275s ago
,E/SMD     (  290): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,I/ServiceManager(  336): Waiting for service AtCmdFwd...

```
