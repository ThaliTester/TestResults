#### Test 50650278eab32a5_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,I/qtaguid ( 7300): Untagging socket 34
W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
W/ApiaryClient( 7300): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6720085839495664559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
--------- beginning of system
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7379): 
D/AndroidRuntime( 7379): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7379): CheckJNI is OFF
D/AndroidRuntime( 7379): setted country_code = Germany
D/AndroidRuntime( 7379): setted countryiso_code = DE
D/AndroidRuntime( 7379): setted sales_code = DBT
D/AndroidRuntime( 7379): readGMSProperty: start
D/AndroidRuntime( 7379): readGMSProperty: already setted!!
D/AndroidRuntime( 7379): readGMSProperty: end
D/AndroidRuntime( 7379): addProductProperty: start
E/AffinityControl( 7379): AffinityControl: registerfunction enter
D/AndroidRuntime( 7379): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  896): inState():  stateMachine is null !!
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  896): mDVFSHelper.acquire()
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  896): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7390 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7390): MountEmulatedStorage()
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
E/Zygote  ( 7390): v2
I/libpersona( 7390): KNOX_SDCARD checking this for 10367
I/libpersona( 7390): KNOX_SDCARD not a persona
I/SELinux ( 7390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SELinux ( 7390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7390): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 7379): Shutting down VM
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/TimaKeyStoreProvider( 7390): TimaSignature is unavailable
D/ActivityThread( 7390): Added TimaKeyStore provider
V/ActivityManager(  896): Display changed displayId=0
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SurfaceFlinger(  251): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/SurfaceFlinger(  251): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7390): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
E/BooksSync( 7300): Soft error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6720085839495664559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7300): Sync error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6720085839495664559&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7300): Finished books sync
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 67833, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  896): Killing 6279:com.google.android.talk/u0a117 (adj 15): bgCount ##41
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  896): failed to open /acct/uid_10117/pid_6279/cgroup.procs: No such file or directory
I/WebViewFactory( 7390): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7390): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7390): Loading: webviewchromium
I/LibraryLoader( 7390): Time to load native libraries: 2 ms (timestamps 6733-6735)
I/LibraryLoader( 7390): Expected native library version number "",actual native library version number ""
I/art     (  896): Explicit concurrent mark sweep GC freed 47697(2MB) AllocSpace objects, 19(499KB) LOS objects, 30% free, 36MB/52MB, paused 1.304ms total 106.858ms
D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
V/WebViewChromiumFactoryProvider( 7390): Binding Chromium to main looper Looper (main, tid 1) {3b901be8}
I/LibraryLoader( 7390): Expected native library version number "",actual native library version number ""
I/chromium( 7390): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7390): Initializing chromium process, renderers=0
W/art     ( 7390): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7390): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7390): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7390): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7390): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7390): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7390): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7390): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7390): Remote Branch: 
I/Adreno-EGL( 7390): Local Patches: 
I/Adreno-EGL( 7390): Reconstruct Branch: 
W/chromium( 7390): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7390): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7390): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7390): onDetachedFromWindow called when already detached. Ignoring
W/ActivityManager(  896): Activity pause timeout for ActivityRecord{39e130f0 u0 com.test.thalitest/.MainActivity t12}
D/SystemWebViewEngine( 7390): CordovaWebView is running on device made by: samsung
W/art     ( 7390): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7390): Attempt to remove local handle scope entry from IRT, ignoring
I/GAV2    ( 7300): Thread[GAThread,5,main]: No campaign data found.
D/Activity( 7390): performCreate Call secproduct feature valuefalse
D/Activity( 7390): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7390): Render dirty regions requested: true
D/ActivityManager(  896): post active user change for 0
D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
I/SurfaceFlinger(  251): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
I/OpenGLRenderer( 7390): Initialized EGL, version 1.4
I/OpenGLRenderer( 7390): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/OpenGLRenderer( 7390): Enabling debug mode 0
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
W/ActivityManager(  896): mDVFSHelper.release()
I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{39e130f0 u0 com.test.thalitest/.MainActivity t12} time:97396
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
W/IInputConnectionWrapper( 7390): showStatusIcon on inactive InputConnection
I/Timeline( 7390): Timeline: Activity_idle id: android.os.BinderProxy@3b97e2fb time:97398
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/chromium( 7390): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7390): 
,E/SMD     (  280): DCD ON
,D/JsMessageQueue( 7390): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7390): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358533504
,D/JX-Cordova( 7390): jxcore cordova android initializing
,W/jxcore-log( 7390): Initializing JXcore engine
,W/jxcore-log( 7390): JXcore engine is ready
,W/jxcore-log( 7390): Starting JXcore engine
,E/auditd  ( 2094): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  896): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  896): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7487): MountEmulatedStorage()
E/Zygote  ( 7487): v2
I/libpersona( 7487): KNOX_SDCARD checking this for 1000
I/libpersona( 7487): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7487): TimaSignature is unavailable
,D/ActivityThread( 7487): Added TimaKeyStore provider
,D/ResourcesManager( 7487): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7390): Platform android
W/jxcore-log( 7390): 
W/jxcore-log( 7390): Process ARCH arm
W/jxcore-log( 7390): 
,D/SecurityLogAgent( 7487):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7487):  SeDenialReceiver : File path = null
,I/ActivityManager(  896): Killing 6559:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,W/libprocessgroup(  896): failed to open /acct/uid_10075/pid_6559/cgroup.procs: No such file or directory
,I/jxcore-log( 7390): JXcore Cordova bridge is ready!
I/jxcore-log( 7390): 
,W/jxcore-log( 7390): JXcore engine is started
I/Choreographer( 7390): Skipped 125 frames!  The application may be doing too much work on its main thread.
,E/jxcore  ( 7390): Error!: missing ) after argument list
E/jxcore  ( 7390): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 7390): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/ActivityManager(  896): Killing 6582:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ScreenOrientationListener( 7390): Removing an inexistent observer!
,W/ActivityManager(  896): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,I/SurfaceFlinger(  251): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  251): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,E/ViewRootImpl( 7390): sendUserActionEvent() mView == null
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6582/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 20
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 20
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 20
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3764): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3764): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  896): post active user change for 0
,D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,I/SurfaceFlinger(  251): id=16 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7390): showStatusIcon on inactive InputConnection
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,I/art     ( 3764): Background partial concurrent mark sweep GC freed 33008(2MB) AllocSpace objects, 45(720KB) LOS objects, 49% free, 16MB/32MB, paused 6.150ms total 34.114ms
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/Timeline( 3764): Timeline: Activity_idle id: android.os.BinderProxy@1f59493f time:100539
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,W/ActivityManager(  896): mDVFSHelper.release()
I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{cd12540 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t11} time:100556
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 3
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/TaskPersister(  896): removeObsoleteFile: deleting file=11_task.xml
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,I/PowerManagerService(  896): [PWL] Off : 30s ago
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 350, PST = 419, CUR = 300
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6661): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6661): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6661): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON,
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 330, PST = 409, CUR = 300
,D/X       (  896): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7559): MountEmulatedStorage()
,E/Zygote  ( 7559): v2
I/libpersona( 7559): KNOX_SDCARD checking this for 10054
,I/libpersona( 7559): KNOX_SDCARD not a persona
,D/ContentApp( 1224):  LEVEL : -1
,I/SELinux ( 7559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  314): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 539us total 35.002ms
,I/ActivityManager(  896): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7559 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 391us total 20.897ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 394us total 21.423ms
,I/SystemBroadcastReceiver( 7133): [#DCM#] [DCM_Performance] onReceive completed in time  18339 microsec. 
,I/SystemBroadcastReceiver( 7133): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7133): [#DCM#] onReceive action = EVENT_SIOP
,D/TimaKeyStoreProvider( 7559): TimaSignature is unavailable
,D/ActivityThread( 7559): Added TimaKeyStore provider
,D/ResourcesManager( 7559): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7559): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7559): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7559): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7559): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7559): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 7559): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 7559): core_num = 4
,W/linker  ( 7559): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 7559): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 7559): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 7559): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 7559):  SIOP_LEVEL: -1
,I/ActivityManager(  896): Killing 6619:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6619/cgroup.procs: No such file or directory
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/FactoryTest( 6497): Not factory mode
,D/FactoryTest( 6497): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6497): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6497): still no open session command from host, so toast
,W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6497): Timeline: Activity_launch_request id:com.android.settings time:115319
,E/PersonaManagerService(  896): inState():  stateMachine is null !!
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  896): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6497): started activity for popup
,I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6497): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6497): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6497): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  896): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2df8a8ac attribute=null, token = android.os.BinderProxy@1d358b88
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6497): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6497): dev.kiessupport is : TRUE
,D/Activity( 6497): performCreate Call secproduct feature valuefalse
,D/Activity( 6497): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 20
,E/SMD     (  280): DCD ON
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 20
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 20
I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3764): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 3764): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  896): post active user change for 0
D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,I/DBG_DM  ( 3764): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,I/Timeline( 3764): Timeline: Activity_idle id: android.os.BinderProxy@1f59493f time:115915
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ActivityManager(  896): mDVFSHelper.release()
,E/SMD     (  280): DCD ON
,D/TaskPersister(  896): removeObsoleteFile: deleting file=11_task.xml
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1716): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6634): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at dsf.a(PG:807)
E/HttpOperation( 6634): 	at fhk.a(PG:1126)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 8 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 10 more
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6634): [getaccountstatus] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at ixd.a(PG:248)
E/HttpOperation( 6634): 	at ixd.b(PG:206)
E/HttpOperation( 6634): 	at ixd.a(PG:175)
E/HttpOperation( 6634): 	at fig.a(PG:78)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/EsSyncAdapterService( 6634): Sync failure
E/EsSyncAdapterService( 6634): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6634): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6634): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6634): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6634): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6634): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6634): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6634): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6634): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6634): 	... 10 more
E/EsSyncAdapterService( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6634): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6634): 	... 12 more
E/EsSyncAdapterService( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6634): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6634): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6634): 	... 14 more
D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6634): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at dsf.a(PG:807)
E/HttpOperation( 6634): 	at fhk.a(PG:1126)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 8 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 10 more
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at ieo.a(PG:43)
E/HttpOperation( 6634): 	at iep.a(PG:93)
E/HttpOperation( 6634): 	at fhn.a(PG:59)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/ExperimentLoader( 6634): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): 	at kfv.a(PG:65)
E/ExperimentLoader( 6634): 	at kff.u(PG:385)
E/ExperimentLoader( 6634): 	at kfb.a(PG:29)
E/ExperimentLoader( 6634): 	at kff.l(PG:132)
E/ExperimentLoader( 6634): 	at ieo.a(PG:43)
E/ExperimentLoader( 6634): 	at iep.a(PG:93)
E/ExperimentLoader( 6634): 	at fhn.a(PG:59)
E/ExperimentLoader( 6634): 	at lex.a(PG:85)
E/ExperimentLoader( 6634): 	at lex.b(PG:132)
E/ExperimentLoader( 6634): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6634): 	at fhk.a(PG:908)
E/ExperimentLoader( 6634): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6634): 	at ihi.a(PG:22)
E/ExperimentLoader( 6634): 	at kft.a(PG:91)
E/ExperimentLoader( 6634): 	at kfv.a(PG:62)
E/ExperimentLoader( 6634): 	... 12 more
E/ExperimentLoader( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6634): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6634): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6634): 	at ihi.a(PG:19)
E/ExperimentLoader( 6634): 	... 14 more
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getaccountstatus] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at ixd.a(PG:248)
E/HttpOperation( 6634): 	at ixd.b(PG:206)
E/HttpOperation( 6634): 	at ixd.a(PG:175)
E/HttpOperation( 6634): 	at fig.a(PG:78)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/EsSyncAdapterService( 6634): Sync failure
E/EsSyncAdapterService( 6634): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6634): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6634): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6634): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6634): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6634): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6634): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6634): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6634): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6634): 	... 10 more
E/EsSyncAdapterService( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6634): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6634): 	... 12 more
E/EsSyncAdapterService( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6634): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6634): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6634): 	... 14 more
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 62081, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/PowerManagerService(  896): [PWL] Off : 50s ago
,D/SSRM:m  (  896): SIOP:: AP = 320, PST = 394, CUR = 300
,V/AlarmManager(  896): waitForAlarm result :4
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6661): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6661): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6661): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 4
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 320, PST = 378, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  896): SIOP:: AP = 310, PST = 361, CUR = 300
,V/AlarmManager(  896): waitForAlarm result :4
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6661): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6661): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6661): [1] 5.onFinished: Scheduling replication attempt 4.
,I/art     (  896): Explicit concurrent mark sweep GC freed 46371(2MB) AllocSpace objects, 26(741KB) LOS objects, 30% free, 36MB/52MB, paused 1.849ms total 111.431ms
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 75s ago
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  896): SIOP:: AP = 310, PST = 348, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  896): !@Sync 5
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 337, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 326, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1716): Vacuum at: now=1449668765629 tag=VacuumService
,I/GoogleURLConnFactory( 1716): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1716): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1716): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1716): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1716): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1716): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1716): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1716): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1716): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1716): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1716): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,I/System.out( 1716): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1716): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1716): (HTTPLog)-Thread-202-352403689: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1716): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1716, getuid(): 10012
,I/qtaguid ( 1716): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1716, getuid(): 10012
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1716): No account for auth token provided
,I/qtaguid ( 1716): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1716, getuid(): 10012
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6661): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6661): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6661): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1716): No account for auth token provided
,I/PowerManagerService(  896): [PWL] Off : 105s ago
I/PowerManagerService(  896): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  896): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1716, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=732)
,I/qtaguid ( 1716): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1716, getuid(): 10012
,W/Uploader( 1716): No account for auth token provided
,I/qtaguid ( 1716): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1716, getuid(): 10012
,W/Uploader( 1716):  no longer exists, so no auth token.
,I/qtaguid ( 1716): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1716, getuid(): 10012
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7300): Starting books sync, d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6634): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at dsf.a(PG:807)
E/HttpOperation( 6634): 	at fhk.a(PG:1126)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 8 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 10 more
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,I/art     ( 1716): Explicit concurrent mark sweep GC freed 60161(3MB) AllocSpace objects, 54(3MB) LOS objects, 40% free, 18MB/30MB, paused 3.783ms total 161.104ms
,D/ResourcesManager( 1716): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
D/ResourcesManager( 1716): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6634): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at ieo.a(PG:43)
E/HttpOperation( 6634): 	at iep.a(PG:93)
E/HttpOperation( 6634): 	at fhn.a(PG:59)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/ExperimentLoader( 6634): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): 	at kfv.a(PG:65)
E/ExperimentLoader( 6634): 	at kff.u(PG:385)
E/ExperimentLoader( 6634): 	at kfb.a(PG:29)
E/ExperimentLoader( 6634): 	at kff.l(PG:132)
E/ExperimentLoader( 6634): 	at ieo.a(PG:43)
E/ExperimentLoader( 6634): 	at iep.a(PG:93)
E/ExperimentLoader( 6634): 	at fhn.a(PG:59)
E/ExperimentLoader( 6634): 	at lex.a(PG:85)
E/ExperimentLoader( 6634): 	at lex.b(PG:132)
E/ExperimentLoader( 6634): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6634): 	at fhk.a(PG:908)
E/ExperimentLoader( 6634): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6634): 	at ihi.a(PG:22)
E/ExperimentLoader( 6634): 	at kft.a(PG:91)
E/ExperimentLoader( 6634): 	at kfv.a(PG:62)
E/ExperimentLoader( 6634): 	... 12 more
E/ExperimentLoader( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6634): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6634): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6634): 	at ihi.a(PG:19)
E/ExperimentLoader( 6634): 	... 14 more
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
I/qtaguid ( 7300): Untagging socket 34
W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-94378062270231905&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6634): [getaccountstatus] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at ixd.a(PG:248)
E/HttpOperation( 6634): 	at ixd.b(PG:206)
E/HttpOperation( 6634): 	at ixd.a(PG:175)
E/HttpOperation( 6634): 	at fig.a(PG:78)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
E/EsSyncAdapterService( 6634): Sync failure
E/EsSyncAdapterService( 6634): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6634): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6634): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6634): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6634): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6634): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6634): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6634): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6634): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6634): 	... 10 more
E/EsSyncAdapterService( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6634): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6634): 	... 12 more
E/EsSyncAdapterService( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6634): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6634): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6634): 	... 14 more
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 153334, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-94378062270231905&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 319, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-94378062270231905&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/BooksSync( 7300): Soft error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-94378062270231905&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7300): Sync error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-94378062270231905&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7300): Finished books sync
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161646, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 6
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 314, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6661): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6661): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6661): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 309, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  896): [PWL] Off : 140s ago
,D/SSRM:m  (  896): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/Watchdog(  896): !@Sync 7
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 303, CUR = 300
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 300, CUR = 300
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6634): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at dsf.a(PG:807)
E/HttpOperation( 6634): 	at fhk.a(PG:1126)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 8 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 10 more
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at ieo.a(PG:43)
E/HttpOperation( 6634): 	at iep.a(PG:93)
E/HttpOperation( 6634): 	at fhn.a(PG:59)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
E/ExperimentLoader( 6634): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): 	at kfv.a(PG:65)
E/ExperimentLoader( 6634): 	at kff.u(PG:385)
E/ExperimentLoader( 6634): 	at kfb.a(PG:29)
E/ExperimentLoader( 6634): 	at kff.l(PG:132)
E/ExperimentLoader( 6634): 	at ieo.a(PG:43)
E/ExperimentLoader( 6634): 	at iep.a(PG:93)
E/ExperimentLoader( 6634): 	at fhn.a(PG:59)
E/ExperimentLoader( 6634): 	at lex.a(PG:85)
E/ExperimentLoader( 6634): 	at lex.b(PG:132)
E/ExperimentLoader( 6634): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6634): 	at fhk.a(PG:908)
E/ExperimentLoader( 6634): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6634): 	at ihi.a(PG:22)
E/ExperimentLoader( 6634): 	at kft.a(PG:91)
E/ExperimentLoader( 6634): 	at kfv.a(PG:62)
E/ExperimentLoader( 6634): 	... 12 more
E/ExperimentLoader( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6634): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6634): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6634): 	at ihi.a(PG:19)
E/ExperimentLoader( 6634): 	... 14 more
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getaccountstatus] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at ixd.a(PG:248)
E/HttpOperation( 6634): 	at ixd.b(PG:206)
E/HttpOperation( 6634): 	at ixd.a(PG:175)
E/HttpOperation( 6634): 	at fig.a(PG:78)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/EsSyncAdapterService( 6634): Sync failure
E/EsSyncAdapterService( 6634): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6634): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6634): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6634): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6634): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6634): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6634): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6634): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6634): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6634): 	... 10 more
E/EsSyncAdapterService( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6634): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6634): 	... 12 more
E/EsSyncAdapterService( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6634): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6634): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6634): 	... 14 more
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 243525, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 298, CUR = 300
,I/art     (  896): Explicit concurrent mark sweep GC freed 53176(2MB) AllocSpace objects, 43(1338KB) LOS objects, 30% free, 36MB/52MB, paused 2.345ms total 190.968ms
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  896): !@Sync 8
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  896): [PWL] Off : 180s ago
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 9
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 225s ago
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  896): initializing...
,I/TLC_TIMA_PKM_initialize(  896): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  896): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  896): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  896): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  896): App is not loaded in QSEE
,D/QSEECOMAPI: (  896): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  896): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  896): Trustlet response is completed
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 10
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,E/SMD     (  280): DCD ON
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7300): Starting books sync, d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8551269872179437790&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8551269872179437790&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SMD     (  280): DCD ON
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8551269872179437790&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7300): Soft error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8551269872179437790&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7300): Sync error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8551269872179437790&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7300): Finished books sync
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 316544, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  896): waitForAlarm result :4
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  896): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7852 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7852): MountEmulatedStorage()
,E/Zygote  ( 7852): v2
I/libpersona( 7852): KNOX_SDCARD checking this for 10081
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/libpersona( 7852): KNOX_SDCARD not a persona
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,I/SELinux ( 7852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7852): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7852): TimaSignature is unavailable
,D/ActivityThread( 7852): Added TimaKeyStore provider
,D/ResourcesManager( 7852): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  896): Killing 6726:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,W/libprocessgroup(  896): failed to open /acct/uid_10015/pid_6726/cgroup.procs: No such file or directory
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  896): !@Sync 11
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/PowerManagerService(  896): [PWL] Off : 275s ago
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1716): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
D/PanelView( 1180): There is/are notification(s) 
,E/PlayEventLogger( 6661): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6661): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6661): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6661): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6661): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6661): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6661): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6661): Ignoring header User-Agent because its value was null.
,I/System.out( 6661): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6661): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6661): (HTTPLog)-Thread-1093-49894636: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 12
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6634): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at dsf.a(PG:807)
E/HttpOperation( 6634): 	at fhk.a(PG:1126)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 8 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 10 more
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
E/HttpOperation( 6634): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at ieo.a(PG:43)
E/HttpOperation( 6634): 	at iep.a(PG:93)
E/HttpOperation( 6634): 	at fhn.a(PG:59)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
E/ExperimentLoader( 6634): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): 	at kfv.a(PG:65)
E/ExperimentLoader( 6634): 	at kff.u(PG:385)
E/ExperimentLoader( 6634): 	at kfb.a(PG:29)
E/ExperimentLoader( 6634): 	at kff.l(PG:132)
E/ExperimentLoader( 6634): 	at ieo.a(PG:43)
E/ExperimentLoader( 6634): 	at iep.a(PG:93)
E/ExperimentLoader( 6634): 	at fhn.a(PG:59)
E/ExperimentLoader( 6634): 	at lex.a(PG:85)
E/ExperimentLoader( 6634): 	at lex.b(PG:132)
E/ExperimentLoader( 6634): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6634): 	at fhk.a(PG:908)
E/ExperimentLoader( 6634): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6634): 	at ihi.a(PG:22)
E/ExperimentLoader( 6634): 	at kft.a(PG:91)
E/ExperimentLoader( 6634): 	at kfv.a(PG:62)
E/ExperimentLoader( 6634): 	... 12 more
E/ExperimentLoader( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6634): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6634): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6634): 	at ihi.a(PG:19)
E/ExperimentLoader( 6634): 	... 14 more
,I/art     ( 1716): Explicit concurrent mark sweep GC freed 40805(2MB) AllocSpace objects, 33(2MB) LOS objects, 40% free, 18MB/30MB, paused 1.589ms total 87.432ms
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1716): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getaccountstatus] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at ixd.a(PG:248)
E/HttpOperation( 6634): 	at ixd.b(PG:206)
E/HttpOperation( 6634): 	at ixd.a(PG:175)
E/HttpOperation( 6634): 	at fig.a(PG:78)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/EsSyncAdapterService( 6634): Sync failure
E/EsSyncAdapterService( 6634): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6634): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6634): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6634): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6634): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6634): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6634): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6634): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6634): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6634): 	... 10 more
E/EsSyncAdapterService( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6634): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6634): 	... 12 more
E/EsSyncAdapterService( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6634): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6634): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6634): 	... 14 more
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 365356, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON,
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 13
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 330s ago
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 14
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  896): !@Sync 15
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 390s ago
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/bootchecker(  317): bootchecker wake up!!
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 16
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 17
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/PowerManagerService(  896): [PWL] Off : 455s ago
,E/SMD     (  280): DCD ON
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 18
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7300): Starting books sync, d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1716): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7300): null auth token
,D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
,W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5101739723437743304&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Atfwd_Daemon(  321): Stop the daemon....
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
I/qtaguid ( 7300): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5101739723437743304&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  896): !@Sync 19
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5101739723437743304&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7300): Soft error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5101739723437743304&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7300): Sync error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5101739723437743304&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7300): Finished books sync
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 581076, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  896): Explicit concurrent mark sweep GC freed 61374(4MB) AllocSpace objects, 113(2MB) LOS objects, 30% free, 36MB/52MB, paused 2.045ms total 195.152ms
D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 525s ago
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  896): !@Sync 20
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ActivityManager(  896): Killing 6747:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,W/libprocessgroup(  896): failed to open /acct/uid_10016/pid_6747/cgroup.procs: No such file or directory
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6634): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at dsf.a(PG:807)
E/HttpOperation( 6634): 	at fhk.a(PG:1126)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 8 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 10 more
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at ieo.a(PG:43)
E/HttpOperation( 6634): 	at iep.a(PG:93)
E/HttpOperation( 6634): 	at fhn.a(PG:59)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/ExperimentLoader( 6634): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): 	at kfv.a(PG:65)
E/ExperimentLoader( 6634): 	at kff.u(PG:385)
E/ExperimentLoader( 6634): 	at kfb.a(PG:29)
E/ExperimentLoader( 6634): 	at kff.l(PG:132)
E/ExperimentLoader( 6634): 	at ieo.a(PG:43)
E/ExperimentLoader( 6634): 	at iep.a(PG:93)
E/ExperimentLoader( 6634): 	at fhn.a(PG:59)
E/ExperimentLoader( 6634): 	at lex.a(PG:85)
E/ExperimentLoader( 6634): 	at lex.b(PG:132)
E/ExperimentLoader( 6634): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6634): 	at fhk.a(PG:908)
E/ExperimentLoader( 6634): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6634): 	at ihi.a(PG:22)
E/ExperimentLoader( 6634): 	at kft.a(PG:91)
E/ExperimentLoader( 6634): 	at kfv.a(PG:62)
E/ExperimentLoader( 6634): 	... 12 more
E/ExperimentLoader( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6634): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6634): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6634): 	at ihi.a(PG:19)
E/ExperimentLoader( 6634): 	... 14 more
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getaccountstatus] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at ixd.a(PG:248)
E/HttpOperation( 6634): 	at ixd.b(PG:206)
E/HttpOperation( 6634): 	at ixd.a(PG:175)
E/HttpOperation( 6634): 	at fig.a(PG:78)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/EsSyncAdapterService( 6634): Sync failure
E/EsSyncAdapterService( 6634): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6634): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6634): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6634): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6634): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6634): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6634): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6634): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6634): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6634): 	... 10 more
E/EsSyncAdapterService( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6634): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6634): 	... 12 more
E/EsSyncAdapterService( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6634): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6634): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6634): 	... 14 more
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 619470, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2846): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2846): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog(  896): !@Sync 21
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  896): !@Sync 22
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 600s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 23
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 24
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 680s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 25
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 26
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 285, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 283, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 281, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 27
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 279, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 277, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 765s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 28
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 29
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  896): !@Sync 30
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 273, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 855s ago
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/LightsService(  896): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  896): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  896): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2496): Aggregate from 1449667118655 (log), 1449667118655 (data)
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1716): Message class com.google.f.a.a.i
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCM     ( 2496): Message from null null
,E/GCM     ( 2496): Dropping message from null
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 1
,E/LightSensor(  896): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  896): unregisterListener ::   
D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 290, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 31
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 32
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  896): stay LED for fully charged
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 33
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 950s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 34
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 35
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 36
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,E/SMD     (  280): DCD ON
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7300): Starting books sync, d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8997340311115634446&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8997340311115634446&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,W/GLSActivity( 1716): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1716): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1716): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1716): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1716): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7300): Authentication error
E/BooksAccountManager( 7300): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7300): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7300): null auth token
,I/qtaguid ( 7300): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7300, getuid(): 10082
,I/qtaguid ( 7300): Untagging socket 34
,W/ApiaryClient( 7300): Error response from books API: {
W/ApiaryClient( 7300):  "error": {
W/ApiaryClient( 7300):   "errors": [
W/ApiaryClient( 7300):    {
W/ApiaryClient( 7300):     "domain": "global",
W/ApiaryClient( 7300):     "reason": "required",
W/ApiaryClient( 7300):     "message": "Login Required",
W/ApiaryClient( 7300):     "locationType": "header",
W/ApiaryClient( 7300):     "location": "Authorization"
W/ApiaryClient( 7300):    }
W/ApiaryClient( 7300):   ],
W/ApiaryClient( 7300):   "code": 401,
W/ApiaryClient( 7300):   "message": "Login Required"
W/ApiaryClient( 7300):  }
W/ApiaryClient( 7300): }
,W/ApiaryClient( 7300): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8997340311115634446&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7300): Headers suppressed
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7300): Soft error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8997340311115634446&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7300): Sync error
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7300): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8997340311115634446&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7300): Headers suppressed
E/BooksSync( 7300): 
E/BooksSync( 7300): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7300): Finished books sync
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1105769, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 37
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1050s ago
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6634): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at dsf.a(PG:807)
E/HttpOperation( 6634): 	at fhk.a(PG:1126)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 8 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 10 more
,I/PhoneStatusBar( 1180): Icon Only
D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): There is/are notification(s) 
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
E/HttpOperation( 6634): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at kff.l(PG:132)
E/HttpOperation( 6634): 	at ieo.a(PG:43)
E/HttpOperation( 6634): 	at iep.a(PG:93)
E/HttpOperation( 6634): 	at fhn.a(PG:59)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,D/PanelView( 1180): There is/are notification(s) 
E/ExperimentLoader( 6634): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6634): 	at kfv.a(PG:65)
E/ExperimentLoader( 6634): 	at kff.u(PG:385)
E/ExperimentLoader( 6634): 	at kfb.a(PG:29)
E/ExperimentLoader( 6634): 	at kff.l(PG:132)
E/ExperimentLoader( 6634): 	at ieo.a(PG:43)
E/ExperimentLoader( 6634): 	at iep.a(PG:93)
E/ExperimentLoader( 6634): 	at fhn.a(PG:59)
E/ExperimentLoader( 6634): 	at lex.a(PG:85)
E/ExperimentLoader( 6634): 	at lex.b(PG:132)
E/ExperimentLoader( 6634): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6634): 	at fhk.a(PG:908)
E/ExperimentLoader( 6634): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6634): 	at ihi.a(PG:22)
E/ExperimentLoader( 6634): 	at kft.a(PG:91)
E/ExperimentLoader( 6634): 	at kfv.a(PG:62)
E/ExperimentLoader( 6634): 	... 12 more
E/ExperimentLoader( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6634): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6634): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6634): 	at ihi.a(PG:19)
E/ExperimentLoader( 6634): 	... 14 more
D/PanelView( 1180): There is/are notification(s) 
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1716): Explicit concurrent mark sweep GC freed 36435(2MB) AllocSpace objects, 26(2MB) LOS objects, 39% free, 18MB/30MB, paused 687us total 50.107ms
,D/ResourcesManager( 1716): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1716): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
,D/SecContentProvider2(  896): mCursor = null
D/SecContentProvider2(  896): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1180): Icon Only
,D/LockPatternUtilsCache( 1180): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1180): value : false
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): There is/are notification(s) 
,E/HttpOperation( 6634): [getaccountstatus] Unexpected exception
E/HttpOperation( 6634): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6634): 	at kfv.a(PG:65)
E/HttpOperation( 6634): 	at kff.u(PG:385)
E/HttpOperation( 6634): 	at kfb.a(PG:29)
E/HttpOperation( 6634): 	at ixd.a(PG:248)
E/HttpOperation( 6634): 	at ixd.b(PG:206)
E/HttpOperation( 6634): 	at ixd.a(PG:175)
E/HttpOperation( 6634): 	at fig.a(PG:78)
E/HttpOperation( 6634): 	at lex.a(PG:85)
E/HttpOperation( 6634): 	at lex.b(PG:132)
E/HttpOperation( 6634): 	at fhk.a(PG:1146)
E/HttpOperation( 6634): 	at fhk.a(PG:908)
E/HttpOperation( 6634): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6634): 	at ihi.a(PG:22)
E/HttpOperation( 6634): 	at kft.a(PG:91)
E/HttpOperation( 6634): 	at kfv.a(PG:62)
E/HttpOperation( 6634): 	... 12 more
E/HttpOperation( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6634): 	at gde.c(Unknown Source)
E/HttpOperation( 6634): 	at gde.b(Unknown Source)
E/HttpOperation( 6634): 	at ihi.a(PG:19)
E/HttpOperation( 6634): 	... 14 more
,E/EsSyncAdapterService( 6634): Sync failure
E/EsSyncAdapterService( 6634): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6634): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6634): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6634): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6634): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6634): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6634): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6634): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6634): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6634): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6634): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6634): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6634): 	... 10 more
E/EsSyncAdapterService( 6634): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6634): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6634): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6634): 	... 12 more
E/EsSyncAdapterService( 6634): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6634): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6634): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6634): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6634): 	... 14 more
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1125476, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  896): Explicit concurrent mark sweep GC freed 68808(5MB) AllocSpace objects, 179(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.349ms total 97.007ms
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 38
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 39
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  896): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  896): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  896): Updating Usage Statistics in DB @ 1449669799233
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  896): Done Updating Usage Statistics in DB @ 1449669799515
,E/Watchdog(  896): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 280, PST = 272, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1155s ago
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 41
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 42
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 43
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  280): DCD ON
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 44
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  896): stay LED for fully charged
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  896): [PWL] Off : 1265s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 45
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  896): !@Sync 46
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 47
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  896): waitForAlarm result :8
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,E/SMD     (  280): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 48
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1380s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 269, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 268, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 267, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 49
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 266, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 265, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  896): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 264, CUR = 300
,E/Watchdog(  896): !@Sync 51
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 300
,E/Watchdog(  896): !@Sync 52
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1500s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 300
,E/Watchdog(  896): !@Sync 53
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 300
,E/Watchdog(  896): !@Sync 54
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  896): !@Sync 55
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,E/SMD     (  280): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  896): !@Sync 56
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1625s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  896): !@Sync 57
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  896): !@Sync 58
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  896): !@Sync 59
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  896): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 261, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1755s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 261, CUR = 300
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/LightsService(  896): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  896): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,I/ProcessStatsService(  896): Prepared write state in 31ms
,D/SensorManager(  896): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  896): Prepared write state in 16ms
,V/NetworkStats(  896): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  896): performPollLocked() took 31ms
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Netstats( 2496): User is not opted-in to Usage & Diagnostics.
,E/LightSensor(  896): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 4, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=4, cpl=3202560
D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  896): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  896): unregisterListener ::   
,D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/GLSUser ( 1716): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1716): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1716): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1716): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1716): Message class com.google.f.a.a.i
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ProcessStatsService(  896): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-10-51.bin
,E/SMD     (  280): DCD ON
,E/SQLiteLog( 1716): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 270, PST = 262, CUR = 300
,E/Watchdog(  896): !@Sync 61
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/BatteryService(  896): stay LED for fully charged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 300
,E/Watchdog(  896): !@Sync 62
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3242): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  896): SIOP:: AP = 260, PST = 262, CUR = 300
,E/Watchdog(  896): !@Sync 63
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  896): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  896):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1180):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3242): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3242): Disconnected process message: 10
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 8265): 
D/AndroidRuntime( 8265): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8265): CheckJNI is OFF
D/AndroidRuntime( 8265): setted country_code = Germany
D/AndroidRuntime( 8265): setted countryiso_code = DE
D/AndroidRuntime( 8265): setted sales_code = DBT
D/AndroidRuntime( 8265): readGMSProperty: start
D/AndroidRuntime( 8265): readGMSProperty: already setted!!
D/AndroidRuntime( 8265): readGMSProperty: end
D/AndroidRuntime( 8265): addProductProperty: start
E/AffinityControl( 8265): AffinityControl: registerfunction enter
D/AndroidRuntime( 8265): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  896): START PACKAGE DELETE: observer{524180062}
D/PackageManager(  896): pkg{<packageName>}
D/PackageManager(  896): user{0}
D/PackageManager(  896): caller{2000}
D/PackageManager(  896): flags{3}
D/PersonaManagerService(  896): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  896): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  896): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  896): Killing 7390:com.test.thalitest/u0a367 (adj 15): stop com.test.thalitest
I/ActivityManager(  896): Killing 7169:com.sec.android.app.music:service/u0a44 (adj 15): empty for 1846s
I/ActivityManager(  896): Killing 7133:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1846s
I/ActivityManager(  896): Killing 6201:com.google.android.gm/u0a114 (adj 15): empty for 1847s
I/ActivityManager(  896): Killing 7112:com.sec.android.app.samsungapps/u0a40 (adj 15): empty for 1847s
I/ActivityManager(  896): Killing 7092:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1847s
I/ActivityManager(  896): Killing 6702:com.google.android.gms:car/u0a12 (adj 15): empty for 1847s
I/ActivityManager(  896): Killing 7077:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1847s
I/ActivityManager(  896): Killing 7042:com.samsung.helphub/1000 (adj 15): empty for 1847s
I/ActivityManager(  896): Killing 7025:com.samsung.android.magazine.service/u0a118 (adj 15): empty for 1847s
I/ActivityManager(  896): Killing 7007:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): empty for 1848s
I/ActivityManager(  896): Killing 6985:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1848s
I/ActivityManager(  896): Killing 6968:com.sec.android.provider.logsprovider/u0a20 (adj 15): empty for 1848s
I/ActivityManager(  896): Killing 6957:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1848s
I/ActivityManager(  896): Killing 6895:com.sec.android.automotive.drivelink/u0a99 (adj 15): empty for 1848s
I/ActivityManager(  896): Killing 6922:com.vlingo.midas/u0a33 (adj 15): empty for 1848s
I/ActivityManager(  896): Killing 6867:com.google.android.apps.docs/u0a98 (adj 15): empty for 1848s
I/ActivityManager(  896): Killing 6597:com.sec.chaton/u0a86 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6259:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6848:com.sec.android.app.soundalive/u0a58 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6830:com.sec.android.app.myfiles/u0a51 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 5656:com.android.mms/u0a50 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6806:com.osp.app.signin/u0a45 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6050:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 5216:com.sec.spp.push/u0a38 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6786:com.policydm/1000 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 4738:com.sec.android.app.shealth/u0a35 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6531:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): empty for 1850s
I/ActivityManager(  896): Killing 6767:com.sec.pcw.device/1000 (adj 15): empty for 1850s
W/PackageSettings(  896): Skipping PackageSetting{de5f424 com.example.hello/10374} due to missing metadata
D/CountryDetector(  896): No listener is left
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 4571): Explicit concurrent mark sweep GC freed 3635(203KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 368us total 18.157ms
I/art     ( 1557): Explicit concurrent mark sweep GC freed 39080(2MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 423us total 34.312ms
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1854): mOCRHelper is null
I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 2180): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8294): MountEmulatedStorage()
E/Zygote  ( 8294): v2
I/libpersona( 8294): KNOX_SDCARD checking this for 10019
I/libpersona( 8294): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8294 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 8294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8294): TimaSignature is unavailable
D/ActivityThread( 8294): Added TimaKeyStore provider
D/ResourcesManager( 8294): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/art     (  896): Explicit concurrent mark sweep GC freed 71602(7MB) AllocSpace objects, 244(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.293ms total 164.204ms
I/art     (  896): WaitForGcToComplete blocked for 154.895ms for cause Explicit
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/KLMS-2.4.503: ( 8294): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
I/KLMS-2.4.503: ( 8294): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449670496164
I/KLMS-2.4.503: ( 8294): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8294): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/RegisteredServicesCache( 1471): empty dynamic service
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8310): MountEmulatedStorage()
I/libpersona( 8310): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8310): v2
I/libpersona( 8310): KNOX_SDCARD not a persona
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/ActivityManager(  896): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8310 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 6009:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1847s
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 8310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/SELinux ( 8310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/art     (  896): Explicit concurrent mark sweep GC freed 9361(412KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 1.627ms total 148.048ms
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/TimaKeyStoreProvider( 8310): TimaSignature is unavailable
D/ActivityThread( 8310): Added TimaKeyStore provider
D/ResourcesManager( 8310): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
D/elm:14451( 8310): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8310): ELMEngine.ELMEngine( context ).
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/elm:14451( 8310): MDMBridge.setEnterpriseBridge()
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/elm:14451( 8310): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8310): ElmAgentService : onCreate()
D/elm:14451( 8310): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8310): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8310): MDMBridge.getInstance()
D/elm:14451( 8310): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8310): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/Zygote  ( 8326): MountEmulatedStorage()
I/libpersona( 8326): KNOX_SDCARD checking this for 10017
E/Zygote  ( 8326): v2
I/libpersona( 8326): KNOX_SDCARD not a persona
D/PackageManager(  896): delete codoeFile: 
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/ActivityManager(  896): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8326 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/PackageManager(  896): result of delete: 1{524180062}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/SELinux ( 8326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8326): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 8265): Shutting down VM
D/elm:14451( 8310): ElmAgentService : onDestroy().
I/ActivityManager(  896): Killing 5329:com.google.android.music:main/u0a126 (adj 15): empty for 1847s
D/TimaKeyStoreProvider( 8326): TimaSignature is unavailable
D/ActivityThread( 8326): Added TimaKeyStore provider
D/ResourcesManager( 8326): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/EnterpriseDeviceManagerService(  896): Package has changed for user 0
D/EnterpriseDeviceManagerService(  896): Admin package name: com.google.android.gms
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8326): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8326): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8326): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/Zygote  ( 8342): MountEmulatedStorage()
E/Zygote  ( 8342): v2
I/libpersona( 8342): KNOX_SDCARD checking this for 1000
I/libpersona( 8342): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  896): Killing 4731:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1842s
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/SELinux ( 8342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/SELinux ( 8342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/TimaKeyStoreProvider( 8342): TimaSignature is unavailable
D/ActivityThread( 8342): Added TimaKeyStore provider
D/ResourcesManager( 8342): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8342): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8342): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8342): new DMDBOpenHelper instance
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/RCPManagerService(  896): PackageReceiver onReceive()
I/HarmonyEASService(  896): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  896): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/PCWCLIENTTRACE_PushUtil( 8342): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8342): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8342): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8342): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService(  896): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
V/EnterpriseBillingPolicy(  896): uID is 10367
V/EnterpriseBillingPolicy(  896): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - exit null
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - end - null
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 8357): MountEmulatedStorage()
E/Zygote  ( 8357): v2
I/libpersona( 8357): KNOX_SDCARD checking this for 10034
I/libpersona( 8357): KNOX_SDCARD not a persona
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/ActivityManager(  896): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8357 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  896): Killing 5060:com.android.defcontainer/u0a5 (adj 15): empty for 1840s
D/TaskPersister(  896): removeObsoleteFile: deleting file=12_task.xml
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
I/SELinux ( 8357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8357): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8357): TimaSignature is unavailable
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ActivityThread( 8357): Added TimaKeyStore provider
W/ResourcesManager(  896): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  896): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8357): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/FeatureConfig( 8357): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_7042/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10166/pid_7077/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10112/pid_7007/cgroup.procs: No such file or directory
D/UsbSettingsManager(  896): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  896): onPackageRemoved : com.test.thalitest
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6767/cgroup.procs: No such file or directory
D/ResourcesManager( 8357): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/libprocessgroup(  896): failed to open /acct/uid_10033/pid_6922/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6259/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10044/pid_7169/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10040/pid_7112/cgroup.procs: No such file or directory
W/ResourcesManager( 8357): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/libprocessgroup(  896): failed to open /acct/uid_10045/pid_6806/cgroup.procs: No such file or directory
W/ResourcesManager( 8357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6985/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10035/pid_4738/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10099/pid_6895/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10003/pid_6957/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10058/pid_6848/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10020/pid_6968/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10012/pid_6702/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10086/pid_6597/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10098/pid_6867/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10051/pid_6830/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10114/pid_6201/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10118/pid_7025/cgroup.procs: No such file or directory
D/ResourcesManager( 8357): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/libprocessgroup(  896): failed to open /acct/uid_10034/pid_6531/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10050/pid_5656/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10170/pid_7092/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10004/pid_7133/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6786/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10038/pid_5216/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10042/pid_6050/cgroup.procs: No such file or directory
W/ResourcesManager( 8357): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 8357): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8357): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/libprocessgroup(  896): failed to open /acct/uid_10048/pid_6009/cgroup.procs: No such file or directory
D/ResourcesManager( 8357): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 8357): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8357): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 8357): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8357): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.

```
