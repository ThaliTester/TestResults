#### Test 550731521dbc378_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  854): uri = 14 selection = getSealedState
D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7387): null auth token
I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,I/qtaguid ( 7387): Untagging socket 34
W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
W/ApiaryClient( 7387): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6551835406950623626&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
--------- beginning of system
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7457): 
D/AndroidRuntime( 7457): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7457): CheckJNI is OFF
D/AndroidRuntime( 7457): setted country_code = Germany
D/AndroidRuntime( 7457): setted countryiso_code = DE
D/AndroidRuntime( 7457): setted sales_code = DBT
D/AndroidRuntime( 7457): readGMSProperty: start
D/AndroidRuntime( 7457): readGMSProperty: already setted!!
D/AndroidRuntime( 7457): readGMSProperty: end
D/AndroidRuntime( 7457): addProductProperty: start
E/AffinityControl( 7457): AffinityControl: registerfunction enter
D/AndroidRuntime( 7457): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  854): inState():  stateMachine is null !!
V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  854): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  854): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  854): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  854): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3576): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3576): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/AndroidRuntime( 7457): Shutting down VM
E/BooksSync( 7387): Soft error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6551835406950623626&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7387): Sync error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6551835406950623626&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7387): Finished books sync
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63242, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/ActivityManager(  854): Killing 6597:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
I/DBG_DM  ( 3740): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 43
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3740): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3740): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3740): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  854): mCursor = null
W/libprocessgroup(  854): failed to open /acct/uid_10075/pid_6597/cgroup.procs: No such file or directory
I/DBG_DM  ( 3740): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  854): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 854) 
D/LightsService(  854): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  854): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  854): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1174): Icon Only
D/SecContentProvider2(  854): uri = 14 selection = getSealedState
D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  854): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3740): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
V/BitmapFactory( 1174): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3740): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1174): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/KnoxNotification( 1174): ----- inflateViews : modified publicViewLocal -----
E/Zygote  ( 7484): MountEmulatedStorage()
E/Zygote  ( 7484): v2
I/libpersona( 7484): KNOX_SDCARD checking this for 10367
I/libpersona( 7484): KNOX_SDCARD not a persona
I/ActivityManager(  854): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7484 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/KnoxNotification( 1174): ----- inflateViews : modified KnoxViewLocal -----
I/SELinux ( 7484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/PersonaManager( 1174): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1174): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@1e34b5b8
I/SELinux ( 7484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/SecContentProvider2(  854): uri = 14 selection = getSealedState
D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
E/SELinux ( 7484): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
D/TimaKeyStoreProvider( 7484): TimaSignature is unavailable
D/ActivityThread( 7484): Added TimaKeyStore provider
V/ActivityManager(  854): Display changed displayId=0
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/StatusBarManagerService(  854): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/ResourcesManager( 7484): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/WebViewFactory( 7484): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7484): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PowerManagerService(  854): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1174 (0x0)
I/LibraryLoader( 7484): Loading: webviewchromium
I/LibraryLoader( 7484): Time to load native libraries: 3 ms (timestamps 6390-6393)
I/LibraryLoader( 7484): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
V/WebViewChromiumFactoryProvider( 7484): Binding Chromium to main looper Looper (main, tid 1) {100f05f5}
I/LibraryLoader( 7484): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/chromium( 7484): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7484): Initializing chromium process, renderers=0
W/art     ( 7484): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7484): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7484): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7484): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/Adreno-EGL( 7484): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7484): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7484): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7484): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7484): Remote Branch: 
I/Adreno-EGL( 7484): Local Patches: 
I/Adreno-EGL( 7484): Reconstruct Branch: 
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
W/chromium( 7484): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7484): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
W/art     ( 7484): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7484): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/SystemWebViewEngine( 7484): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
W/art     ( 7484): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7484): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/Activity( 7484): performCreate Call secproduct feature valuefalse
D/Activity( 7484): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/OpenGLRenderer( 7484): Render dirty regions requested: true
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/ActivityManager(  854): post active user change for 0
D/KnoxTimeoutHandler(  854): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  854): handleActiveUserChange for user 0
I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/OpenGLRenderer( 7484): Initialized EGL, version 1.4
I/OpenGLRenderer( 7484): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7484): Enabling debug mode 0
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/InputMethodManagerService(  854): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Adreno-ES20( 7484): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7484): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/ActivityManager(  854): Displayed com.test.thalitest/.MainActivity: +655ms
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/GAV2    ( 7387): Thread[GAThread,5,main]: No campaign data found.
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/Timeline( 7484): Timeline: Activity_idle id: android.os.BinderProxy@2bcb735c time:96840
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/JsMessageQueue( 7484): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
V/AlarmManager(  854): waitForAlarm result :4
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/chromium( 7484): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7484): 
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/CustomFrequencyManagerService(  854): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  854): mDVFSHelper.release()
,I/Timeline(  854): Timeline: Activity_windows_visible id: ActivityRecord{cc9b37c u0 com.test.thalitest/.MainActivity t12} time:97015
,D/CustomFrequencyManagerService(  854): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/SSRM:m  (  854): SIOP:: AP = 350, PST = 418, CUR = 300
,D/jxcore_app_log( 7484): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358533504
,D/JX-Cordova( 7484): jxcore cordova android initializing
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6706): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6706): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6706): [1] 5.onFinished: Scheduling replication attempt 2.
,D/CustomFrequencyManagerService(  854): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  tag : ACTIVITY_RESUME_BOOSTER@10
,E/SMD     (  286): DCD ON
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,W/jxcore-log( 7484): Initializing JXcore engine
,W/jxcore-log( 7484): JXcore engine is ready
,W/jxcore-log( 7484): Starting JXcore engine
,E/auditd  ( 2095): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  854): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  854): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7544 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 7544): MountEmulatedStorage()
E/Zygote  ( 7544): v2
,I/libpersona( 7544): KNOX_SDCARD checking this for 1000
I/libpersona( 7544): KNOX_SDCARD not a persona
,I/SELinux ( 7544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7544): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7544): TimaSignature is unavailable
,D/ActivityThread( 7544): Added TimaKeyStore provider
,D/ResourcesManager( 7544): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7484): Platform android
W/jxcore-log( 7484): 
,W/jxcore-log( 7484): Process ARCH arm
W/jxcore-log( 7484): 
,D/SecurityLogAgent( 7544):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7544):  SeDenialReceiver : File path = null
,I/ActivityManager(  854): Killing 6614:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6614/cgroup.procs: No such file or directory
,I/jxcore-log( 7484): JXcore Cordova bridge is ready!
I/jxcore-log( 7484): 
,W/jxcore-log( 7484): JXcore engine is started
,D/TaskPersister(  854): removeObsoleteFile: deleting file=11_task_thumbnail.png
,D/PowerManagerService(  854): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  854): getFinalBrightness : 15 -> 15
D/PowerManagerService(  854): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  854): lcd : 52 +
,D/lights  (  854): lcd : 52 -
,D/lights  (  854): lcd : 44 +
,D/lights  (  854): lcd : 44 -
,D/lights  (  854): lcd : 35 +
,D/lights  (  854): lcd : 35 -
,D/lights  (  854): lcd : 27 +
,D/lights  (  854): lcd : 27 -
,D/lights  (  854): lcd : 19 +
,D/lights  (  854): lcd : 19 -
,D/DisplayPowerController(  854): getFinalBrightness : 15 -> 15
,D/lights  (  854): lcd : 15 +
,D/lights  (  854): lcd : 15 -
,D/DisplayPowerController(  854): getFinalBrightness : 15 -> 15
,I/jxcore-log( 7484): Toggling radios to true
I/jxcore-log( 7484): 
,D/BluetoothAdapter( 7484): enable()
,D/BluetoothAdapter( 7484): enable(): BT is already enabled..!
,I/WifiManager( 7484): packageName : com.test.thalitest
,D/SecContentProvider(  854): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  854): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  854): mCursor = null
,D/WifiService(  854): setWifiEnabled: true pid=7484, uid=10367
,E/WifiService(  854): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  854): Permission Denial: getCurrentUser() from pid=7484, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  854): Failed getting userId using ActivityManagerNative
W/WifiService(  854): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7484, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  854): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  854): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  854): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  854): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  854): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  854): name = wifi_on
,I/WifiService(  854): disconnect: pid=7484, uid=10367
,I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7484): Radios toggled
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): Received device characteristics:
I/jxcore-log( 7484): Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7484): Bluetooth name: Thali Test (Galaxy S5)
I/jxcore-log( 7484): Device name: samsung-SM-G900F
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): Perf Test app loaded loaded
I/jxcore-log( 7484): 
,I/wpa_supplicant( 1293): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1293): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  854): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1293): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): Disconnected - do not scan
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  854): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  854): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  854): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/chromium( 7484): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/WifiStateMachine(  854): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  854): InactiveState{ what=143375 }
,D/WifiP2pService(  854): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1710): Read error: ssl=0xaf14de00: I/O error during system call, Connection timed out
,I/jxcore-log( 7484): check test folder
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): found test : ./testFindPeers.js
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): found test : ./testSendData.js
I/jxcore-log( 7484): 
,E/WifiStateMachine(  854): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/SMD     (  286): DCD ON
,E/ConnectivityService(  854): updateNetworkInfo()
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,I/WifiTrafficPoller(  854): evaluateTrafficStatsPolling
,I/CLocInfoService(  854): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  854): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 1293): First Scan Start
I/wpa_supplicant( 1293): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  854): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  854): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  854): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  854): InactiveState{ what=143375 }
,D/WifiP2pService(  854): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  280): Clearing all IP addresses on wlan0
D/ConnectivityService(  854): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  854): calling update connectivity
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity(  854): Not allowed due to - mEnabled false
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  854): requiresClat: netType=1, connected=false, hasIPv4Address=true
,E/WifiStateMachine(  854): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524292
D/ConnectivityService(  854): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  854): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  854): updateConfiguredNetworkExpiration - currTime: 1451989116210
D/WifiStateMachine(  854): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,E/WifiStateMachine(  854): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
I/WifiTrafficPoller(  854): evaluateTrafficStatsPolling
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  854): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  854): Disconnected - quitting
,I/CLocInfoService(  854): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  854): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  854): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  854): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  854): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  854): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  854): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  854): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  854): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  854): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  854): mCursor = null
,D/CSLegacyTypeTracker(  854): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker(  854): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/TelephonyNetworkFactory( 1467): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2(  854): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  854): mCursor = null
,D/SmartBondingService(  854): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  854): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
,V/NetworkStats(  854): updateIfacesLocked()
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
V/NetworkStats(  854): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  854): UpdateStatsForKnox
,E/ConnectivityService(  854): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  854): performPollLocked() took 21ms
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,I/Choreographer( 7484): Skipped 81 frames!  The application may be doing too much work on its main thread.
,I/art     (  854): Explicit concurrent mark sweep GC freed 41236(2MB) AllocSpace objects, 13(1878KB) LOS objects, 29% free, 38MB/54MB, paused 16.783ms total 293.702ms
,D/WifiService(  854): New client listening to asynchronous messages
,V/NativeCrypto( 1710): SSL shutdown failed: ssl=0xaf14de00: I/O error during system call, Broken pipe
,I/Hs20UtilService( 1304): Starting #6
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/SmartBondingService(  854): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
V/NetworkStats(  854): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/chromium( 7484): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1304): Starting #7
,I/Hs20UtilService( 1304): Message received 5007
D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  854): updateDataUsageMap
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  854): MasterInitialState.processMessage what=3
,D/SmartBondingService(  854): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  854): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  854): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  854): CLoinfo wifi false
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2258): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SystemBroadcastReceiver( 7201): [#DCM#] [DCM_Performance] onReceive completed in time  4844 microsec. 
,W/SLocation(  854): No Active Data Connection
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7201): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7201): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7201): [#DCM#] setIsConnectedForExtractors 
,I/NetworkMonitor( 5384): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3740): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/PCWCLIENTTRACE_PushUtil( 6816): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6816): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6816): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6816): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6816): noConnectivity : true
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3740): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7605): MountEmulatedStorage()
,E/Zygote  ( 7605): v2
I/libpersona( 7605): KNOX_SDCARD checking this for 10002
I/libpersona( 7605): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7605 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 346us total 13.700ms
,I/SELinux ( 7605): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7605): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7605): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 9.712ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 8.053ms
,D/TimaKeyStoreProvider( 7605): TimaSignature is unavailable
,D/ActivityThread( 7605): Added TimaKeyStore provider
,D/ResourcesManager( 7605): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  854): Killing 6660:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7631): MountEmulatedStorage()
E/Zygote  ( 7631): v2
I/libpersona( 7631): KNOX_SDCARD checking this for 1000
I/libpersona( 7631): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7631 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6660/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7631): TimaSignature is unavailable
,D/ActivityThread( 7631): Added TimaKeyStore provider
,D/ResourcesManager( 7631): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7631): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7631): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7631): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7631): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7631): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7631): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7650): MountEmulatedStorage()
,E/Zygote  ( 7650): v2
I/libpersona( 7650): KNOX_SDCARD checking this for 10011
I/libpersona( 7650): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7650 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7650): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7650): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7650): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7650): TimaSignature is unavailable
,D/ActivityThread( 7650): Added TimaKeyStore provider
,D/ResourcesManager( 7650): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1293): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1293): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1293): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1293): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  854): [1,451,989,117,247 ms] noteScanEnd no scan source
,E/WifiStateMachine(  854): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@293ca166 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  854): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  854): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  854): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  854): setDetailed state send new extra info0x
,D/SecContentProvider2(  854): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  854): mCursor = null
,I/ActivityManager(  854): Killing 6778:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/FOTA_Client( 7650): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7650): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7650): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7650): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7650): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  854): failed to open /acct/uid_10015/pid_6778/cgroup.procs: No such file or directory
,E/Zygote  ( 7665): MountEmulatedStorage()
E/Zygote  ( 7665): v2
I/libpersona( 7665): KNOX_SDCARD checking this for 10019
I/libpersona( 7665): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7665 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 6800:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SELinux ( 7665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1293): Associated with C0.AA.48
,E/WifiStateMachine(  854): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  854): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,W/libprocessgroup(  854): failed to open /acct/uid_10016/pid_6800/cgroup.procs: No such file or directory
,D/SecContentProvider2(  854): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  854): mCursor = null
,D/TimaKeyStoreProvider( 7665): TimaSignature is unavailable
,D/ActivityThread( 7665): Added TimaKeyStore provider
,D/ResourcesManager( 7665): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  854): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  854): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  854): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  854): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  854): mCursor = null
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1293): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1293): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1293): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1293): Blacklist: Clear (temp) 
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  854): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  854): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  854): Network connection established
,D/WifiNative-HAL(  854): callSECApiVoid - ID [50]
,E/WifiStateMachine(  854): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  854): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  854): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  854): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  854): Got NetworkAgent Messenger
D/ConnectivityService(  854): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  854): updateNetworkInfo()
,D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854): NetworkAgent connected
E/WifiStateMachine(  854): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/KLMS-2.4.503: ( 7665): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7665): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1451989117389
,I/KLMS-2.4.503: ( 7665): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  854): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  854): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  854): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  854): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/KLMS-2.4.503: ( 7665): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7665): StateImplV2(): networkChangeListener().END
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine(  854): Start Dhcp Watchdog 2
,I/CLocInfoService(  854): External Intent Received android.net.wifi.STATE_CHANGE
,D/SecContentProvider2(  854): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  854): mCursor = null
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ActivityManager(  854): Killing 6567:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  854): calculateWifiScore() report new score 60
I/WifiStateMachine(  854): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  854): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,D/ConnectivityService(  854): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  854): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  854): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7682): MountEmulatedStorage()
E/Zygote  ( 7682): v2
I/libpersona( 7682): KNOX_SDCARD checking this for 10037
I/libpersona( 7682): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7682 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7682): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  854): failed to open /acct/uid_10034/pid_6567/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7682): TimaSignature is unavailable
,D/ActivityThread( 7682): Added TimaKeyStore provider
,D/ResourcesManager( 7682): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7682): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/WifiStateMachine(  854): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  854): do suspend false
,D/WifiP2pService(  854): InactiveState{ what=143375 }
,D/WifiP2pService(  854): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  854): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  854): mCursor = null
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5117): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6854): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6854): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6854): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6854): [SLFUCHKMGR] constructor called
,I/SA      ( 6854): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
E/SPPClientService( 5117): [[SystemStateMonitorService]] No Active Internet
I/SA      ( 6854): [OR] == isSIMCardReady false ==
,I/SA      ( 6854): [SCU] == networkStateCheck == false
I/SA      ( 6854): [OR] onReceive END
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7703): MountEmulatedStorage()
,E/Zygote  ( 7703): v2
I/libpersona( 7703): KNOX_SDCARD checking this for 10071
I/libpersona( 7703): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7703 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  854): Killing 4602:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7703): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7703): TimaSignature is unavailable
,D/ActivityThread( 7703): Added TimaKeyStore provider
,D/ResourcesManager( 7703): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup(  854): failed to open /acct/uid_10035/pid_4602/cgroup.procs: No such file or directory
,D/comsamsunglog( 7703): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7703): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7703): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7703): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7703): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7703): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7703): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7703): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  854): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 10071
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7703): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7703): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7703): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7703): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7703): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7703): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7703): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7703): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7703): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7703): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7721): MountEmulatedStorage()
E/Zygote  ( 7721): v2
I/libpersona( 7721): KNOX_SDCARD checking this for 1000
I/libpersona( 7721): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7721 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 6110:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7721): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7721): TimaSignature is unavailable
,D/ActivityThread( 7721): Added TimaKeyStore provider
,E/dhcpcd  ( 7729): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7729): version 5.5.6 starting
,E/dhcpcd  ( 7729): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ResourcesManager( 7721): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7721): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7721): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7721): premStatus:2
,I/KnoxUsageLogPro( 7721): isEulaShown : false
I/KnoxUsageLogPro( 7721): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  854): failed to open /acct/uid_10042/pid_6110/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7729): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7729): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7729): if(wlan0) info get Success. (MAC : C0.AA.48)
E/Zygote  ( 7746): MountEmulatedStorage()
,E/Zygote  ( 7746): v2
I/libpersona( 7746): KNOX_SDCARD checking this for 10088
I/libpersona( 7746): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7729): bssid match
I/dhcpcd  ( 7729): wlan0: rebinding lease of 192.168.1.135
,I/ActivityManager(  854): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7746 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 5717:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7746): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7746): TimaSignature is unavailable
,D/ActivityThread( 7746): Added TimaKeyStore provider
,D/CountryDetector(  854): No listener is left
,D/ResourcesManager( 7746): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  854): failed to open /acct/uid_10050/pid_5717/cgroup.procs: No such file or directory
,I/ActivityManager(  854): Killing 6877:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5521): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5521): getCountryCode(): countryCode = DE
,D/Headlines( 5521): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5521): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5521): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5521): requestUpdateNewsWelcomeCard !!! no welcome card
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7762): MountEmulatedStorage()
,E/Zygote  ( 7762): v2
I/libpersona( 7762): KNOX_SDCARD checking this for 10128
I/libpersona( 7762): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7762 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7762): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7762): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7762): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7762): TimaSignature is unavailable
,D/ActivityThread( 7762): Added TimaKeyStore provider
,D/ResourcesManager( 7762): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  854): failed to open /acct/uid_10051/pid_6877/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7762): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7762): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7762): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7762): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7762): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7762): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7762): Loading: webviewchromium
,I/LibraryLoader( 7762): Time to load native libraries: 4 ms (timestamps 2764-2768)
,I/LibraryLoader( 7762): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7762): Binding Chromium to main looper Looper (main, tid 1) {11d289bb}
,I/LibraryLoader( 7762): Expected native library version number "",actual native library version number ""
,I/chromium( 7762): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7762): Initializing chromium process, renderers=0
,W/art     ( 7762): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7762): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7762): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7762): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7762): Requires BLUETOOTH permission
,I/Adreno-EGL( 7762): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7762): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7762): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7762): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7762): Remote Branch: 
I/Adreno-EGL( 7762): Local Patches: 
I/Adreno-EGL( 7762): Reconstruct Branch: 
,I/NSApplication( 7762): Starting up...
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  854): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7820 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 6895:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,E/Zygote  ( 7820): MountEmulatedStorage()
E/Zygote  ( 7820): v2
I/libpersona( 7820): KNOX_SDCARD checking this for 10138
I/libpersona( 7820): KNOX_SDCARD not a persona
,I/dhcpcd  ( 7729): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/SELinux ( 7820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7820): TimaSignature is unavailable
,D/ActivityThread( 7820): Added TimaKeyStore provider
,D/ResourcesManager( 7820): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,I/dhcpcd  ( 7729): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  854): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  854): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,W/libprocessgroup(  854): failed to open /acct/uid_10058/pid_6895/cgroup.procs: No such file or directory
,W/ResourcesManager( 7820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7820): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7820): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7820): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7820): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7820): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7855): MountEmulatedStorage()
,E/Zygote  ( 7855): v2
I/libpersona( 7855): KNOX_SDCARD checking this for 10163
I/libpersona( 7855): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7855 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 6256:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7855): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7855): TimaSignature is unavailable
,D/ActivityThread( 7855): Added TimaKeyStore provider
,D/ResourcesManager( 7855): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7855): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7855): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7855): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_6256/cgroup.procs: No such file or directory
,E/WifiStateMachine(  854): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  854): InactiveState{ what=143375 }
,D/WifiP2pService(  854): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  854): WifiStateMachine DHCP successful
,E/WifiStateMachine(  854): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  854): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  854): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  854): Not connected state, yet.
E/WifiStateMachine(  854): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  854): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  854): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  854): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  854): callSECApiInt - ID [210]
,E/WifiStateMachine(  854): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  854): updateNetworkInfo()
,D/ConnectivityService(  854): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  854): Adding iface wlan0 to network 503
,I/CLocInfoService(  854): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  854): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  854): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  854): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  854): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  854): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,D/ConnectivityService(  854): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine(  854): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  854): Now, connected state.
E/WifiStateMachine(  854): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  854): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  854): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/WifiTrafficPoller(  854): evaluateTrafficStatsPolling
,I/CLocInfoService(  854): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  854): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  854): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  854): mBoosterFLAG : 0
,I/WifiTrafficPoller(  854): current booster mode : FullMode
D/WifiNative-HAL(  854): callSECApiVoid - ID [212]
,E/WifiStateMachine(  854): ConnectedState Enter  mScreenOn=true scanperiod=20000
,I/CLocInfoService(  854): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  854): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ConnectivityService(  854): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  854): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  854): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  280): QcRouteController
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiStateMachine(  854): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,V/        (  280): QcRouteController
,E/Zygote  ( 7901): MountEmulatedStorage()
I/libpersona( 7901): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7901): v2
I/libpersona( 7901): KNOX_SDCARD not a persona
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  854): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7901 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/        (  280): QcRouteController
,I/art     (  312): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 11.675ms
,V/        (  280): QcRouteController
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 243us total 8.111ms
,V/        (  280): QcRouteController
,I/SELinux ( 7901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7901): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 7.881ms
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/        (  280): QcRouteController
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,D/ConnectivityService(  854): Setting Dns servers for network 503 to [/192.168.1.1]
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,D/TimaKeyStoreProvider( 7901): TimaSignature is unavailable
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
D/ActivityThread( 7901): Added TimaKeyStore provider
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
D/Nat464Xlat(  854): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  854): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  854): updateNetworkInfo()
D/ConnectivityService(  854): calling update connectivity
E/ConnectivityService(  854): updateNetworkInfo()
D/ConnectivityService(  854): ignoring duplicate network state non-change
D/ConnectivityService(  854): ignoring duplicate network state non-change
D/ConnectivityService(  854): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
D/ConnectivityService(  854): calling update connectivity
D/ConnectivityService(  854): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  854):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854): currentScore = 0, newScore = 60
D/ConnectivityService(  854):    accepting network in place of null
D/ConnectivityService(  854): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  854): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  854): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  854): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  854): Validated
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
E/CSLegacyTypeTracker(  854): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  854): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
D/TelephonyNetworkFactory( 1467): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,I/ActivityManager(  854): Killing 6916:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,D/ConnectivityService(  854): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
D/ConnectivityService(  854): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  854): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  854): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/ConnectivityService(  854): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  854): calling update connectivity
,V/NetworkStats(  854): updateIfacesLocked()
V/NetworkStats(  854): performPollLocked(flags=0x1)
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
,D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NetworkStatsFactory(  854): UpdateStatsForKnox
D/ConnectivityService(  854): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
D/ConnectivityService(  854): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  854):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/ConnectivityService(  854): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/ConnectivityService(  854): calling update connectivity
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  854): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/SmartBondingService(  854): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
V/NetworkStats(  854): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
,V/NetworkStats(  854): performPollLocked() took 7ms
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/NtpTrustedTime(  854): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/SecurityLogAgent( 7544): KnoxConfiguration : Current State = 1
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
D/SecurityLogAgent( 7544): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7544): StateMachine : Current State = 1
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/SecurityLogAgent( 7544): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/ActivityManager(  854): Killing 6980:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,D/ResourcesManager( 7901): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): last run: 1451989033275 -- System.currentTimeMillis()-last_run: 85676
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip last_72_check
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7901): onCreate
D/BadgeProvider( 7901): DatabaseHelper
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
V/BitmapFactory( 7855): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,E/Zygote  ( 7924): MountEmulatedStorage()
I/libpersona( 7924): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7924): v2
I/libpersona( 7924): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7924 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7924): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7901): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7901): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7901): sendNotify, [notify] : null
D/BadgeProvider( 7901): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7901): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7901): update, [UpdateCount] : 1
,D/Launcher.Model( 1490): reloadBadges entered.
,D/TimaKeyStoreProvider( 7924): TimaSignature is unavailable
,D/ActivityThread( 7924): Added TimaKeyStore provider
,D/ResourcesManager( 7924): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  854): Killing 6952:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  854): failed to open /acct/uid_10098/pid_6916/cgroup.procs: No such file or directory
W/libprocessgroup(  854): failed to open /acct/uid_10033/pid_6980/cgroup.procs: No such file or directory
,E/Watchdog(  854): !@Sync 3
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  854): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2420): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2420): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  854): failed to open /acct/uid_10099/pid_6952/cgroup.procs: No such file or directory
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7179): notifyNetworkActivated
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SMD     (  286): DCD ON
V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7179): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  854): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2420): [AccountUtils] Account not ready
W/Kids    ( 2420): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2420): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2420): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2420): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2420): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2420): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2420): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2420): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,D/hcjo    ( 7179): AutoUpdateManager:IDLE:execute
,I/Hs20UtilService( 1304): Starting #8
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/InitializeManagerStateMachine( 7179): execute::IDLE:EXECUTE
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7179): exit::IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
D/InitializeManagerStateMachine( 7179): entry::NETWORK_CHECK
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7179): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7179): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7179): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7179): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7179): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7179): entry::SUCCESS
D/hcjo    ( 7179): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7179): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7179): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 1304): Starting #9
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7179): exit::SUCCESS
D/InitializeManagerStateMachine( 7179): entry::IDLE
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1304): Message received 5007
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #10
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1304): Message received 5007
V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #11
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  854): callSECApi what=220
D/WifiStateMachine(  854): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/PowerManagerService(  854): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=854
,D/DisplayPowerController(  854): getFinalBrightness : 54 -> 54
,D/PowerManagerService(  854): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/lights  (  854): lcd : 22 +
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/lights  (  854): lcd : 22 -
,D/lights  (  854): lcd : 30 +
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/lights  (  854): lcd : 30 -
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/lights  (  854): lcd : 39 +
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/lights  (  854): lcd : 39 -
,D/lights  (  854): lcd : 47 +
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/lights  (  854): lcd : 47 -
,D/DisplayPowerController(  854): getFinalBrightness : 54 -> 54
D/lights  (  854): lcd : 54 +
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  854): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  854): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  854): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  854): MasterInitialState.processMessage what=3
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  854): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  854): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  854): CLocinfo wifi true 
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2258): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/lights  (  854): lcd : 54 -
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/DisplayPowerController(  854): getFinalBrightness : 54 -> 54
,D/LockPatternUtilsCache( 1174): value : false
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  854): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2171): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SystemBroadcastReceiver( 7201): [#DCM#] [DCM_Performance] onReceive completed in time  376 microsec. 
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5384): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3740): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3740): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,I/PCWCLIENTTRACE_PushUtil( 6816): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6816): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6816): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6816): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7201): [#DCM#] Calling notifyListeners. 
I/DCMController( 7201): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7201): [#DCM#] setIsConnectedForExtractors 
,I/DatabaseRebuilderTask( 7201): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 7631): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7631): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  854): mCursor = null
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/FrameworkService( 7201): [#DCM#] onCreate FrameworkService 
I/FrameworkService( 7201): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7201): [#DCM#] getSuccessState = true
,I/FrameworkService( 7201): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7201): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SystemUtils( 7201): [#DCM#] LM: false,AM:688992256
,I/DCMThreadPoolExecutor( 7201): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7201): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@13aa2d5 is submitted
I/FrameworkService( 7201): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 27174 mirosec. 
,I/DatabaseRebuilderTask( 7201): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7201): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7201): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7201): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7201): [#DCM#] No of Location data to be added:  0
I/DatabaseRebuilderTask( 7201): [#DCM#] releaseLuceneReader done 
,I/DatabaseRebuilderTask( 7201): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7201): [#DCM#] setHeavySharedPref set as  false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/IntentHandler( 7201): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7201): [#DCM#] afterExecute FutureTask
I/DCMController( 7201): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@13aa2d5
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/FOTA_Client( 7650): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7650): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7650): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7650): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7650): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7665): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/KLMS-2.4.503: ( 7665): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1451989119574
,I/KLMS-2.4.503: ( 7665): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7665): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7665): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7665): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7665): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SO_AGENT( 7682): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5117): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/SA      ( 6854): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6854): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6854): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6854): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6854): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6854): [SCU] == networkStateCheck == true
,I/SA      ( 6854): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6854): isChinaCountryCode : false
I/SA      ( 6854): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6854): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SA      ( 6854): [OR] GetMyCountryZoneTask
,I/SA      ( 6854): [OR] onReceive END
,I/SA      ( 6854): [SRS] prepareGetMyCountryZone
,I/SA      ( 6854): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6854): [SSP] query invoked
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6854): [TPMU] GetMccFromDB : null
,I/SA      ( 6854): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6854): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/accuweather( 7703): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7703): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7721): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7721): premStatus:2
,I/KnoxUsageLogPro( 7721): isEulaShown : false
I/KnoxUsageLogPro( 7721): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/Headlines( 5521): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5521): getCountryCode(): countryCode = DE
,E/File    ( 6854): fail readDirectory() errno=2
,D/Headlines( 5521): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5521): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5521): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5521): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7820): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7820): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7820): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,D/RCPManagerService(  854): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7544): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7544): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7544): StateMachine : Current State = 1
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7544): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): last run: 1451989033275 -- System.currentTimeMillis()-last_run: 86475
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip last_72_check
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2420): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ChimeraCfgMgr( 2420): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7179): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7179): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7179): exit::IDLE
D/InitializeManagerStateMachine( 7179): entry::NETWORK_CHECK
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7179): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7179): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7179): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7179): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7179): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7179): entry::SUCCESS
D/hcjo    ( 7179): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/hcjo    ( 7179): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7179): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7179): exit::SUCCESS
,D/InitializeManagerStateMachine( 7179): entry::IDLE
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2420): [AccountUtils] Account not ready
W/Kids    ( 2420): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2420): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2420): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2420): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2420): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2420): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2420): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2420): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2420): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      ( 6854): [RC New] Execute method=[GET] start
,I/SA      ( 6854): [RC New] Security=[true]
,I/System.out( 6854): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6854): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 6854): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,I/SA      ( 6854): [RC New] [v2liruge] api execute + 662,
,I/SA      ( 6854): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6854): AsyncTask #1 calls detatch()
,I/SA      ( 6854): [ODM] saveOpenData( GEO_IP, PL )
,I/art     (  854): Explicit concurrent mark sweep GC freed 61635(3MB) AllocSpace objects, 3(178KB) LOS objects, 29% free, 38MB/54MB, paused 1.806ms total 123.152ms
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7484): BLE is supported
I/jxcore-log( 7484): 
,I/SA      ( 6854): [OCP] update openData : PL
,I/SA      ( 6854): [TPMU] getNetworkMcc : 
,I/SA      ( 6854): [SCU] saveMccToPreferece Start
I/SA      ( 6854): [SCU] RegionMCC : 260
I/SA      ( 6854): [SSP] query invoked
,I/SA      ( 6854): [TPMU] GetMccFromDB : null
,I/SA      ( 6854): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6854): [SCU] saveMccToPreferece End
,I/SA      ( 6854): [RC New] executeRequest [v2liruge] end. 865
I/SA      ( 6854): [RC New] Execute end
I/SA      ( 6854): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6854): [OR] GetMyCountryZoneTask Success
,D/PowerManagerService(  854): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  854): [PWL] On : 76345 (30002 ms ago)
I/PowerManagerService(  854): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  854): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=854, ws=WorkSource{10059}) (elapsedTime=2553)
,I/dhcpcd  ( 7729): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7729): wlan0: sendmsg: Cannot assign requested address
,I/WifiStateMachine(  854): REQUEST_POWER_SAVE_ON
,E/SMD     (  286): DCD ON
,E/WifiStateMachine(  854): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/SSRM:m  (  854): SIOP:: AP = 390, PST = 415, CUR = 300
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  854): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  854): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  854): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  854): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/SmartBondingService(  854): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  854): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/SmartBondingService(  854): getSBEnabled() enabled =false
D/ConnectivityService(  854): identical MTU - not setting
D/ConnectivityService(  854): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  854): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  280): QcRouteController
,V/        (  280): QcRouteController
,W/NetworkManagementService(  854): route cmd failed: 
W/NetworkManagementService(  854): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  854): '
W/NetworkManagementService(  854): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  854): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  854): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  854): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  854): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  854): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  854): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  854): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  854): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  854): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  854): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  854): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  854): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  854): calling update connectivity
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  854): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  854): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  854): calling update connectivity
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  854):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  854): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/PowerManagerService(  854): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 854) eventTime = 107291
,D/PowerManagerService(  854): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  854): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=854 (0x0)
D/PowerManagerService(  854): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=854, ws=WorkSource{10059}) (elapsedTime=3497)
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,I/GAV4    ( 7762): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  322): result : -1 ,	 ,Init step :2 	 ,qmiErrorCode: 0
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6816): mConnectivityHandler : connected
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6816): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6816): ================================================
,I/CSTORAGE( 6816):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6816): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6816): [GetString-S]
E/art     ( 6816): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6816): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6816): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6816): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6816): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6816): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6816): [ensureRegistration] - No Samsung account
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1710): Connected
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1710): Message class com.google.f.a.a.p
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/dhcpcd  ( 7729): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7179): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7179): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7179): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7179): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7179): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7179): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7179): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7179): entry::IDLE
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,D/PreloadUpdateManagerStateMachine( 7179): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7179): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7179): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7179): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7179): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7179): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7179): entry::IDLE
,I/dhcpcd  ( 7729): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7729): wlan0: no IPv6 Routers available
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,E/SMD     (  286): DCD ON
,D/FactoryTest( 6533): Not factory mode
,D/FactoryTest( 6533): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6533): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6533): still no open session command from host, so toast
,W/ContextImpl( 6533): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6533): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6533): Timeline: Activity_launch_request id:com.android.settings time:115716
,E/PersonaManagerService(  854): inState():  stateMachine is null !!
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  854): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  854): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  854): mDVFSHelper.acquire()
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
E/MTPRx   ( 6533): started activity for popup
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/SQLiteSecureOpenHelper( 3576): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3576): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ResourcesManager( 6533): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6533): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6533): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6533): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6533): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6533): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,E/ActivityManager(  854): Invalid thumbnail dimensions: 576x576
,I/SQLiteSecureOpenHelper( 3576): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3576): getDatabaseLocked(b,b,pwd)...
,D/InputMethodManagerService(  854): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,W/InputMethodManagerService(  854): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2127df63 attribute=null, token = android.os.BinderProxy@733cb6a
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6533): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6533): dev.kiessupport is : TRUE
,D/Activity( 6533): performCreate Call secproduct feature valuefalse
D/Activity( 6533): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ActivityManager(  854): post active user change for 0
D/KnoxTimeoutHandler(  854): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  854): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/Timeline( 7484): Timeline: Activity_idle id: android.os.BinderProxy@2bcb735c time:115963
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,D/SSRM:m  (  854): SIOP:: AP = 340, PST = 403, CUR = 300
D/X       (  854): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/SystemBroadcastReceiver( 7201): [#DCM#] [DCM_Performance] onReceive completed in time  1535 microsec. 
,D/ContentApp( 1226):  LEVEL : -1
,I/SystemBroadcastReceiver( 7201): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7201): [#DCM#] onReceive action = EVENT_SIOP
,E/TranscodeReceiver( 7263): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7263):  SIOP_LEVEL: -1
,V/AlarmManager(  854): waitForAlarm result :4
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6706): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6706): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6706): [1] 5.onFinished: Scheduling replication attempt 3.
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,D/CustomFrequencyManagerService(  854): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  854): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  854): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/CustomFrequencyManagerService(  854): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 854  tag : ACTIVITY_RESUME_BOOSTER@10
,I/ActivityManager(  854): Waited long enough for: ServiceRecord{1737d271 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  854): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  854): SIOP:: AP = 330, PST = 389, CUR = 300
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,E/SMD     (  286): DCD ON
,D/PowerManagerService(  854): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  854): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  854): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  854): lcd : 49 +
,D/lights  (  854): lcd : 49 -
,D/lights  (  854): lcd : 41 +
,D/lights  (  854): lcd : 41 -
,D/lights  (  854): lcd : 32 +
,D/lights  (  854): lcd : 32 -
,D/lights  (  854): lcd : 24 +
,D/lights  (  854): lcd : 24 -
,D/DisplayPowerController(  854): getFinalBrightness : 15 -> 15
,D/lights  (  854): lcd : 15 +
,D/lights  (  854): lcd : 15 -
,D/DisplayPowerController(  854): getFinalBrightness : 15 -> 15
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,E/Watchdog(  854): !@Sync 4
,E/SMD     (  286): DCD ON
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  854): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  854): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 320, PST = 373, CUR = 300
,D/PowerManagerService(  854): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  854): Nap time (uid 1000)...
I/PowerManagerService(  854): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  854): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  854): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  854): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  854): setDeviceInteractive: 0
,D/PowerManagerService(  854): handleSandman : startDream()
,D/InputManager-JNI(  854): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  854): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  854): Sleeping (uid 1000)...
,D/PowerManagerService(  854): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  854): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  854): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  854): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  854): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  854): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  854): 	.unregisterCallback : 1, client=
D/SContextService(  854): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3324c22c, Service = Auto Rotation, used = 1
,W/CAE     (  854): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  854): stop(ContextProvider.java:149)
,V/CAE     (  854): clear(AutoRotationRunner.java:182)
,V/CAE     (  854): disable(AutoRotationRunner.java:171)
,I/CAE     (  854): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  854): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  854): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  854): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  854): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  854): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  854): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  854): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  854): removeSContextService() : service = Auto Rotation
D/SContextService(  854): ===== SContext Service List =====
D/SContextManager(  854):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@33d35488, service=Auto Rotation
,D/KeyguardViewMediator( 1174): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1174): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1174): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1174): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/KeyguardViewMediator( 1174): timeout : 5000
,I/SQLiteSecureOpenHelper( 3576): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3576): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/DisplayPowerController(  854): ColorFade: onAnimationStart
,D/DisplayPowerController(  854): getFinalBrightness : 54 -> 0
,D/lights  (  854): lcd : 9 +
,D/KeyguardViewMediator( 1174): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1174): handleNotifyScreenOff
,D/lights  (  854): lcd : 9 -
D/LightsService(  854): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 854) 
D/LightsService(  854): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/lights  (  854): lcd : 1 +
D/LightsService(  854): [SvcLED]  onSensorChanged::light value = 46
,D/DisplayPowerController(  854): getFinalBrightness : 54 -> 0
,D/SensorManager(  854): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  854): unregisterListener ::   
D/BatteryService(  854): turn on LED for fully charged
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): applyOpen
D/StatusBar.NetworkController( 1174): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): applyOpen
,D/lights  (  854): lcd : 1 -
D/lights  (  854): led_pattern : 5 +
,D/lights  (  854): led_pattern : 5 -
D/lights  (  854): lcd : 0 +
D/LightsService(  854): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  854): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  854): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  854): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  854): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,D/lights  (  854): lcd : 0 -
,I/CAE     (  854): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 10, 19, 13,
D/SensorHubManager(  854): SendSensorHubData: send data = -63, 14, 10, 19, 13
D/Sensorhubs(  297): sendContextData: -63, 14, 10, 19, 13
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  854):  handler : SCREEN_OFF end 
,V/AlarmManager(  854): waitForAlarm result :4
,D/WifiStateMachine(  854): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  854): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  854): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  854): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  854): do suspend true
,D/NotificationService(  854): ACTION_SCREEN_OFF
,D/LightsService(  854): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 854) 
D/LightsService(  854): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  854): [SvcLED]  onSensorChanged::light value = 46
,D/SensorManager(  854): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  854): unregisterListener ::   
D/LightsService(  854): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  854): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  854): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  854): Bridge Server is not available
,D/VolumePanel( 1174): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1174): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1174): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1174): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/PersonaManagerService(  854): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  854): MSG_ACTION_SCREEN_OFF called
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NfcService( 1460): call the applyRotuiing
,D/DisplayPowerState(  854): !@ ColorFade entry
,D/DisplayPowerController(  854): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  854): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  854): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  854): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  854): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  854): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/STATUSBAR-PhoneStatusBar( 1174):      ACTION_SCREEN_OFF is finished!!!! 
,D/SensorManager(  854): unregisterListener ::   
,E/Sensors (  854): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  854): unregisterListener ::   
,E/StatusBar( 1174): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1174): dismissHelpPopup 
,D/accuweather( 2258): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2258): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2258): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerController(  854): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  854): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  854): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  854): Display changed displayId=0
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/StatusBar.NetworkController( 1174): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ActivityManager(  854): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  854): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/SystemBroadcastReceiver( 7201): [#DCM#] [DCM_Performance] onReceive completed in time  252 microsec. 
,I/SystemBroadcastReceiver( 7201): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7201): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7201): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  854): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  854): SIOP:: AP = 320, PST = 361, CUR = 300
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 22
I/rmt_storage(  275): 
,I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  854): Excessive delay in setPowerMode(): 255ms
D/PowerManagerService(  854): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  854): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  854): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  854): Got set_interactive hint
,I/PowerManagerService(  854): [PWL] Off : 0s ago
I/PowerManagerService(  854): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  854): [PWL]     mDisplayReady : false
D/DisplayPowerController(  854): getFinalBrightness : 0 -> 0
D/PowerManagerService(  854): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  854): [PWL] sb release: PowerManagerService.Display
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6706): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6706): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6706): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  854): waitForAlarm result :4
,D/KeyguardViewMediator( 1174): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/KeyguardViewMediator( 1174): doKeyguard: not showing because lockscreen is off
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  854): [PWL] Off : 5s ago
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 310, PST = 352, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  854): [PWL] Off : 15s ago
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,E/HttpOperation( 6675): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at dsf.a(PG:807)
E/HttpOperation( 6675): 	at fhk.a(PG:1126)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 8 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 10 more
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
E/HttpOperation( 6675): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at ieo.a(PG:43)
E/HttpOperation( 6675): 	at iep.a(PG:93)
E/HttpOperation( 6675): 	at fhn.a(PG:59)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,E/ExperimentLoader( 6675): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): 	at kfv.a(PG:65)
E/ExperimentLoader( 6675): 	at kff.u(PG:385)
E/ExperimentLoader( 6675): 	at kfb.a(PG:29)
E/ExperimentLoader( 6675): 	at kff.l(PG:132)
E/ExperimentLoader( 6675): 	at ieo.a(PG:43)
E/ExperimentLoader( 6675): 	at iep.a(PG:93)
E/ExperimentLoader( 6675): 	at fhn.a(PG:59)
E/ExperimentLoader( 6675): 	at lex.a(PG:85)
E/ExperimentLoader( 6675): 	at lex.b(PG:132)
E/ExperimentLoader( 6675): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6675): 	at fhk.a(PG:908)
E/ExperimentLoader( 6675): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6675): 	at ihi.a(PG:22)
E/ExperimentLoader( 6675): 	at kft.a(PG:91)
E/ExperimentLoader( 6675): 	at kfv.a(PG:62)
E/ExperimentLoader( 6675): 	... 12 more
E/ExperimentLoader( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6675): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6675): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6675): 	at ihi.a(PG:19)
E/ExperimentLoader( 6675): 	... 14 more
,E/SMD     (  286): DCD ON
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6675): [getaccountstatus] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at ixd.a(PG:248)
E/HttpOperation( 6675): 	at ixd.b(PG:206)
E/HttpOperation( 6675): 	at ixd.a(PG:175)
E/HttpOperation( 6675): 	at fig.a(PG:78)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,E/EsSyncAdapterService( 6675): Sync failure
E/EsSyncAdapterService( 6675): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6675): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6675): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6675): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6675): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6675): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6675): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6675): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6675): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6675): 	... 10 more
E/EsSyncAdapterService( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6675): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6675): 	... 12 more
E/EsSyncAdapterService( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6675): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6675): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6675): 	... 14 more
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 156926, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  854): mCursor = null
,D/SSRM:m  (  854): SIOP:: AP = 310, PST = 343, CUR = 300
,V/AlarmManager(  854): waitForAlarm result :4
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6706): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6706): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6706): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/Watchdog(  854): !@Sync 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,D/BatteryService(  854): stay LED for fully charged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  854): SIOP:: AP = 300, PST = 333, CUR = 300
,I/PowerManagerService(  854): [PWL] Off : 30s ago
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 300, PST = 327, CUR = 300
,V/AlarmManager(  854): waitForAlarm result :4
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): stay LED for fully charged
D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 1710): Explicit concurrent mark sweep GC freed 42439(2MB) AllocSpace objects, 25(2025KB) LOS objects, 39% free, 17MB/29MB, paused 535us total 36.047ms
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1710): Vacuum at: now=1451989194476 tag=VacuumService
,I/GoogleURLConnFactory( 1710): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1710): No account for auth token provided
,I/System.out( 1710): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1710): (HTTPLog)-Static: isShipBuild true
I/System.out( 1710): (HTTPLog)-Thread-204-915952454: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1710): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1710, getuid(): 10012
,I/qtaguid ( 1710): Tagging socket 61 with tag 120100000000{4609,0} uid -1, pid: 1710, getuid(): 10012
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6706): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6706): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6706): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1710): No account for auth token provided
,I/qtaguid ( 1710): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1710, getuid(): 10012
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,E/Uploader( 1710): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1710): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1710): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1710): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1710): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1710, getuid(): 10012
,W/Uploader( 1710): No account for auth token provided
,I/qtaguid ( 1710): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1710, getuid(): 10012
,W/Uploader( 1710): No account for auth token provided
,I/qtaguid ( 1710): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1710, getuid(): 10012
,W/Uploader( 1710):  no longer exists, so no auth token.
,I/qtaguid ( 1710): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1710, getuid(): 10012
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  854): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  854): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7387): Starting books sync, d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1710): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7387): null auth token
,I/PhoneStatusBar( 1174): Icon Only
I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,E/SMD     (  286): DCD ON
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=755807954700324458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  854): [PWL] Off : 50s ago
,I/PowerManagerService(  854): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  854): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  854): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=854, ws=WorkSource{10082}) (elapsedTime=708)
,D/SSRM:m  (  854): SIOP:: AP = 300, PST = 322, CUR = 300
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=755807954700324458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=755807954700324458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,E/BooksSync( 7387): Soft error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=755807954700324458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7387): Sync error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=755807954700324458&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7387): Finished books sync
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158471, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  854): Explicit concurrent mark sweep GC freed 77282(4MB) AllocSpace objects, 42(3MB) LOS objects, 29% free, 38MB/54MB, paused 1.757ms total 196.082ms
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  854): mCursor = null
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1710): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,E/HttpOperation( 6675): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at dsf.a(PG:807)
E/HttpOperation( 6675): 	at fhk.a(PG:1126)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 8 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 10 more
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6675): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at ieo.a(PG:43)
E/HttpOperation( 6675): 	at iep.a(PG:93)
E/HttpOperation( 6675): 	at fhn.a(PG:59)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,E/ExperimentLoader( 6675): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): 	at kfv.a(PG:65)
E/ExperimentLoader( 6675): 	at kff.u(PG:385)
E/ExperimentLoader( 6675): 	at kfb.a(PG:29)
E/ExperimentLoader( 6675): 	at kff.l(PG:132)
E/ExperimentLoader( 6675): 	at ieo.a(PG:43)
E/ExperimentLoader( 6675): 	at iep.a(PG:93)
E/ExperimentLoader( 6675): 	at fhn.a(PG:59)
E/ExperimentLoader( 6675): 	at lex.a(PG:85)
E/ExperimentLoader( 6675): 	at lex.b(PG:132)
E/ExperimentLoader( 6675): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6675): 	at fhk.a(PG:908)
E/ExperimentLoader( 6675): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6675): 	at ihi.a(PG:22)
E/ExperimentLoader( 6675): 	at kft.a(PG:91)
E/ExperimentLoader( 6675): 	at kfv.a(PG:62)
E/ExperimentLoader( 6675): 	... 12 more
E/ExperimentLoader( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6675): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6675): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6675): 	at ihi.a(PG:19)
E/ExperimentLoader( 6675): 	... 14 more
I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6675): [getaccountstatus] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at ixd.a(PG:248)
E/HttpOperation( 6675): 	at ixd.b(PG:206)
E/HttpOperation( 6675): 	at ixd.a(PG:175)
E/HttpOperation( 6675): 	at fig.a(PG:78)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/PanelView( 1174): There is/are notification(s) 
,E/EsSyncAdapterService( 6675): Sync failure
E/EsSyncAdapterService( 6675): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6675): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6675): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6675): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6675): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6675): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6675): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6675): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6675): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6675): 	... 10 more
E/EsSyncAdapterService( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6675): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6675): 	... 12 more
E/EsSyncAdapterService( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6675): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6675): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6675): 	... 14 more
D/PanelView( 1174): There is/are notification(s) 
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 190064, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  854): mCursor = null
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog(  854): !@Sync 6
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 300, PST = 313, CUR = 300
,E/SMD     (  286): DCD ON,
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 308, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  854): [PWL] Off : 75s ago
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): stay LED for fully charged
D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 304, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog(  854): !@Sync 7
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 301, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  854): [PWL] Off : 105s ago
,V/AlarmManager(  854): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7387): Starting books sync, d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1174): Icon Only
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1999448740640372214&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 296, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1999448740640372214&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,E/SMD     (  286): DCD ON
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1999448740640372214&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/BooksSync( 7387): Soft error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1999448740640372214&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7387): Sync error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1999448740640372214&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7387): Finished books sync
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 222451, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  854): mCursor = null
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  854): !@Sync 8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  854): stay LED for fully charged
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryService(  854): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  854): [PWL] Off : 140s ago
,I/PowerManagerService(  854): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  854): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  854): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=854, ws=WorkSource{10135}) (elapsedTime=223)
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,E/HttpOperation( 6675): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at dsf.a(PG:807)
E/HttpOperation( 6675): 	at fhk.a(PG:1126)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 8 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 10 more
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,E/HttpOperation( 6675): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at ieo.a(PG:43)
E/HttpOperation( 6675): 	at iep.a(PG:93)
E/HttpOperation( 6675): 	at fhn.a(PG:59)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,E/ExperimentLoader( 6675): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): 	at kfv.a(PG:65)
E/ExperimentLoader( 6675): 	at kff.u(PG:385)
E/ExperimentLoader( 6675): 	at kfb.a(PG:29)
E/ExperimentLoader( 6675): 	at kff.l(PG:132)
E/ExperimentLoader( 6675): 	at ieo.a(PG:43)
E/ExperimentLoader( 6675): 	at iep.a(PG:93)
E/ExperimentLoader( 6675): 	at fhn.a(PG:59)
E/ExperimentLoader( 6675): 	at lex.a(PG:85)
E/ExperimentLoader( 6675): 	at lex.b(PG:132)
E/ExperimentLoader( 6675): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6675): 	at fhk.a(PG:908)
E/ExperimentLoader( 6675): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6675): 	at ihi.a(PG:22)
E/ExperimentLoader( 6675): 	at kft.a(PG:91)
E/ExperimentLoader( 6675): 	at kfv.a(PG:62)
E/ExperimentLoader( 6675): 	... 12 more
E/ExperimentLoader( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6675): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6675): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6675): 	at ihi.a(PG:19)
E/ExperimentLoader( 6675): 	... 14 more
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 292, CUR = 300
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1710): Explicit concurrent mark sweep GC freed 59430(3MB) AllocSpace objects, 61(4MB) LOS objects, 40% free, 18MB/30MB, paused 1.321ms total 129.592ms
,D/ResourcesManager( 1710): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,E/HttpOperation( 6675): [getaccountstatus] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at ixd.a(PG:248)
E/HttpOperation( 6675): 	at ixd.b(PG:206)
E/HttpOperation( 6675): 	at ixd.a(PG:175)
E/HttpOperation( 6675): 	at fig.a(PG:78)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,E/EsSyncAdapterService( 6675): Sync failure
E/EsSyncAdapterService( 6675): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6675): 	at ixd.b(PG:206)
,E/EsSyncAdapterService( 6675): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6675): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6675): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6675): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6675): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6675): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6675): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6675): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6675): 	... 10 more
E/EsSyncAdapterService( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6675): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6675): 	... 12 more
E/EsSyncAdapterService( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6675): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6675): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6675): 	... 14 more
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 257163, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  854): mCursor = null
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,E/Watchdog(  854): !@Sync 9
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,D/TimaService(  854): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  854): TimaServiceHandler.handleMessage what =1
,D/TimaService(  854): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  854): initializing...
,I/TLC_TIMA_PKM_initialize(  854): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  854): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  854): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  854): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  854): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  854): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  854): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  854): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  854): App is not loaded in QSEE
,D/QSEECOMAPI: (  854): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  854): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  854): Trustlet response is completed
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  854): !@Sync 10
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  854): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  854): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  854): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  854): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  854): [PWL] Off : 180s ago
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  854): waitForAlarm result :4
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,E/Zygote  ( 8242): MountEmulatedStorage()
,E/Zygote  ( 8242): v2
I/libpersona( 8242): KNOX_SDCARD checking this for 10081
I/libpersona( 8242): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8242 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,I/SELinux ( 8242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,E/SELinux ( 8242): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 8242): TimaSignature is unavailable
,D/ActivityThread( 8242): Added TimaKeyStore provider
,D/ResourcesManager( 8242): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  854): Killing 7013:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,W/libprocessgroup(  854): failed to open /acct/uid_10020/pid_7013/cgroup.procs: No such file or directory
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7387): Starting books sync, d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1710): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3044805894485463243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3044805894485463243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3044805894485463243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/BooksSync( 7387): Soft error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3044805894485463243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7387): Sync error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3044805894485463243&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7387): Finished books sync
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 313751, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  854): Explicit concurrent mark sweep GC freed 60737(3MB) AllocSpace objects, 62(1772KB) LOS objects, 29% free, 38MB/54MB, paused 2.228ms total 177.562ms
D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  854): mCursor = null
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  854): !@Sync 11
,E/SMD     (  286): DCD ON
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1710): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6706): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6706): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6706): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6706): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6706): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6706): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6706): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6706): Ignoring header User-Agent because its value was null.
,I/System.out( 6706): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6706): (HTTPLog)-Static: isShipBuild true
I/System.out( 6706): (HTTPLog)-Thread-1088-512546409: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  854): [PWL] Off : 225s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  854): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  854): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7484): Connected to the server!
I/jxcore-log( 7484): 
,I/chromium( 7484): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/Watchdog(  854): !@Sync 12
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  854): !@Sync 13
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): stay LED for fully charged
D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,E/HttpOperation( 6675): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at dsf.a(PG:807)
E/HttpOperation( 6675): 	at fhk.a(PG:1126)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 8 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 10 more
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6675): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at kff.l(PG:132)
E/HttpOperation( 6675): 	at ieo.a(PG:43)
E/HttpOperation( 6675): 	at iep.a(PG:93)
E/HttpOperation( 6675): 	at fhn.a(PG:59)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,E/ExperimentLoader( 6675): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6675): 	at kfv.a(PG:65)
E/ExperimentLoader( 6675): 	at kff.u(PG:385)
E/ExperimentLoader( 6675): 	at kfb.a(PG:29)
E/ExperimentLoader( 6675): 	at kff.l(PG:132)
E/ExperimentLoader( 6675): 	at ieo.a(PG:43)
E/ExperimentLoader( 6675): 	at iep.a(PG:93)
E/ExperimentLoader( 6675): 	at fhn.a(PG:59)
E/ExperimentLoader( 6675): 	at lex.a(PG:85)
E/ExperimentLoader( 6675): 	at lex.b(PG:132)
E/ExperimentLoader( 6675): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6675): 	at fhk.a(PG:908)
E/ExperimentLoader( 6675): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6675): 	at ihi.a(PG:22)
E/ExperimentLoader( 6675): 	at kft.a(PG:91)
E/ExperimentLoader( 6675): 	at kfv.a(PG:62)
E/ExperimentLoader( 6675): 	... 12 more
E/ExperimentLoader( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6675): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6675): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6675): 	at ihi.a(PG:19)
E/ExperimentLoader( 6675): 	... 14 more
D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
,D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): There is/are notification(s) 
,E/HttpOperation( 6675): [getaccountstatus] Unexpected exception
E/HttpOperation( 6675): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6675): 	at kfv.a(PG:65)
E/HttpOperation( 6675): 	at kff.u(PG:385)
E/HttpOperation( 6675): 	at kfb.a(PG:29)
E/HttpOperation( 6675): 	at ixd.a(PG:248)
E/HttpOperation( 6675): 	at ixd.b(PG:206)
E/HttpOperation( 6675): 	at ixd.a(PG:175)
E/HttpOperation( 6675): 	at fig.a(PG:78)
E/HttpOperation( 6675): 	at lex.a(PG:85)
E/HttpOperation( 6675): 	at lex.b(PG:132)
E/HttpOperation( 6675): 	at fhk.a(PG:1146)
E/HttpOperation( 6675): 	at fhk.a(PG:908)
E/HttpOperation( 6675): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6675): 	at ihi.a(PG:22)
E/HttpOperation( 6675): 	at kft.a(PG:91)
E/HttpOperation( 6675): 	at kfv.a(PG:62)
E/HttpOperation( 6675): 	... 12 more
E/HttpOperation( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6675): 	at gde.c(Unknown Source)
E/HttpOperation( 6675): 	at gde.b(Unknown Source)
E/HttpOperation( 6675): 	at ihi.a(PG:19)
E/HttpOperation( 6675): 	... 14 more
,E/EsSyncAdapterService( 6675): Sync failure
E/EsSyncAdapterService( 6675): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6675): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6675): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6675): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6675): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6675): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6675): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6675): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6675): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6675): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6675): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6675): 	... 10 more
E/EsSyncAdapterService( 6675): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6675): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6675): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6675): 	... 12 more
E/EsSyncAdapterService( 6675): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6675): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6675): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6675): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6675): 	... 14 more
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 408076, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2871): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  854): mCursor = null
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  854): [PWL] Off : 275s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  854): !@Sync 14
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager(  854): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  854): !@Sync 15
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  854): [PWL] Off : 330s ago
,V/AlarmManager(  854): waitForAlarm result :4
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  854): stay LED for fully charged
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7387): Starting books sync, d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4255484562131076697&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4255484562131076697&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1710): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  854): uri = 14 selection = getSealedState
,D/SecContentProvider2(  854): mCursor = null
D/SecContentProvider2(  854): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  854): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  854): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1174): Icon Only
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1710): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1710): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1710): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1710): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7387): Authentication error
E/BooksAccountManager( 7387): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7387): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7387): null auth token
,I/qtaguid ( 7387): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7387, getuid(): 10082
,I/qtaguid ( 7387): Untagging socket 34
,W/ApiaryClient( 7387): Error response from books API: {,
W/ApiaryClient( 7387):  "error": {
W/ApiaryClient( 7387):   "errors": [
W/ApiaryClient( 7387):    {
W/ApiaryClient( 7387):     "domain": "global",
W/ApiaryClient( 7387):     "reason": "required",
W/ApiaryClient( 7387):     "message": "Login Required",
W/ApiaryClient( 7387):     "locationType": "header",
W/ApiaryClient( 7387):     "location": "Authorization"
W/ApiaryClient( 7387):    }
W/ApiaryClient( 7387):   ],
W/ApiaryClient( 7387):   "code": 401,
W/ApiaryClient( 7387):   "message": "Login Required"
W/ApiaryClient( 7387):  }
W/ApiaryClient( 7387): }
,W/ApiaryClient( 7387): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4255484562131076697&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7387): Headers suppressed
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/BooksSync( 7387): Soft error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4255484562131076697&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7387): Sync error
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7387): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4255484562131076697&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7387): Headers suppressed
E/BooksSync( 7387): 
E/BooksSync( 7387): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7387): Finished books sync
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  854): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 466033, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2871): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2871): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  854): mCursor = null
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON,
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/bootchecker(  317): bootchecker wake up!!
,V/AlarmManager(  854): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7484): --- start :testFindPeers.js---
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): testFindPeers created [object Object]
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): serverPort is 8876
I/jxcore-log( 7484): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): initialize: My bluetooth address is B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7484): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7484): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7484): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7484): bindListen(), new LocalSocket 
D/BluetoothSocket( 7484): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7484): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ba7c3f9
D/BluetoothSocket( 7484): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): start: OK
I/io.jxcore.node.ConnectionHelper( 7484): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7484): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7484): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): start: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7484): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  854): InactiveState{ what=139292 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139292 }
D/WifiP2pService(  854): P2pEnabledState add service
,D/WifiP2pService(  854): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): start: Starting P2P device discovery...
,D/WifiP2pService(  854): InactiveState{ what=139265 }
D/WifiP2pService(  854): P2pEnabledState{ what=139265 }
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  854): callSECApi what=74
D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  854): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7484): start: OK
,I/jxcore-log( 7484): StartBroadcasting started ok
I/jxcore-log( 7484): 
,I/io.jxcore.node.ConnectionHelper( 7484): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7484): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7484): onDiscoveryManagerStateChanged: RUNNING
,I/chromium( 7484): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  854): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: RESTARTING
,D/WifiP2pService(  854): InactiveState{ what=139268 }
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiP2pService(  854): InactiveState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState add service request
,D/WifiP2pManager( 7484): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/Watchdog(  854): !@Sync 16
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): Start timer timeout, starting now...
,D/WifiP2pService(  854): InactiveState{ what=139265 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139265 }
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: STARTED
,D/WifiP2pService(  854): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  286): DCD ON
,V/AlarmManager(  854): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  854): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): restart: Restarting...
,D/WifiP2pService(  854): InactiveState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): InactiveState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState add service request
,D/WifiP2pManager( 7484): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  854): InactiveState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7484): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 7484): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 7484): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): weAreDoneNow
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): done, now sending data to server
I/jxcore-log( 7484): 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): restart: Restarting...
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7484): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 7484): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,D/WifiP2pService(  854): InactiveState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
,I/io.jxcore.node.ConnectionHelper( 7484): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 7484): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,D/WifiP2pService(  854): InactiveState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
D/WifiP2pService(  854): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
D/WifiP2pService(  854): P2pEnabledState add service request
D/WifiP2pManager( 7484): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  286): DCD ON
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  854): Plugged
,D/BatteryService(  854): stay LED for fully charged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  286): DCD ON
,E/Watchdog(  854): !@Sync 17
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/SMD     (  286): DCD ON
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 },
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): restart: Restarting...
,D/WifiP2pService(  854): InactiveState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): InactiveState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState add service request
,D/WifiP2pManager( 7484): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  854): [PWL] Off : 390s ago
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 290, CUR = 300
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,E/SMD     (  286): DCD ON
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  854): InactiveState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 7484): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 7484): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,D/WifiP2pService(  854): InactiveState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 7484): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 7484): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  854): InactiveState{ what=147477 }
D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): restart: Restarting...
,D/WifiP2pService(  854): InactiveState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): InactiveState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState add service request
,D/WifiP2pManager( 7484): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,V/AlarmManager(  854): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=6-0050F204-1 name='WorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: WorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 6-0050F204-1, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: WorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: WorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 6-0050F204-1, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: WorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  854): !@Sync 18
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,D/BatteryService(  854): stay LED for fully charged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 270, PST = 286, CUR = 300
,E/SMD     (  286): DCD ON
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7484): onPeerLost: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/io.jxcore.node.ConnectionHelper( 7484): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 7484): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] removed
,D/io.jxcore.node.ConnectionHelper( 7484): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] not available
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 270, PST = 284, CUR = 300
,E/SMD     (  286): DCD ON
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: RESTARTING
,D/WifiP2pService(  854): InactiveState{ what=139268 }
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  854): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 270, PST = 282, CUR = 300
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): Start timer timeout, starting now...
,D/WifiP2pService(  854): InactiveState{ what=139265 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139265 }
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: STARTED
,D/WifiP2pService(  854): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  854): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: RESTARTING
,D/WifiP2pService(  854): InactiveState{ what=139268 }
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): restart: Restarting...
,D/WifiP2pService(  854): InactiveState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): InactiveState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState add service request
,D/WifiP2pManager( 7484): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/Atfwd_Daemon(  322): Stop the daemon....
,E/Watchdog(  854): !@Sync 19
,E/SMD     (  286): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): Start timer timeout, starting now...
,D/WifiP2pService(  854): InactiveState{ what=139265 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139265 }
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  854): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  286): DCD ON
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  286): DCD ON
,D/SSRM:m  (  854): SIOP:: AP = 270, PST = 280, CUR = 300
,I/jxcore-log( 7484): teardown
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): testFindPeers stopped
I/jxcore-log( 7484): 
,I/io.jxcore.node.ConnectionHelper( 7484): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): shutdown
,D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@3c97a6b5, channel: 6, state: LISTENING,
,D/BluetoothSocket( 7484): close() this: android.bluetooth.BluetoothSocket@3c97a6b5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ba7c3f9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@265b514amSocket: android.net.LocalSocket@10e258bb impl:android.net.LocalSocketImpl@30af1d8 fd:FileDescriptor[152]
,D/BluetoothSocket( 7484): Closing mSocket: android.net.LocalSocket@10e258bb impl:android.net.LocalSocketImpl@30af1d8 fd:FileDescriptor[152]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): stop: Stopping services
,D/WifiP2pService(  854): InactiveState{ what=139298 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  854): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7484): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setState: NOT_STARTED
D/WifiP2pService(  854): InactiveState{ what=139268 }
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
,I/jxcore-log( 7484): StopBroadcasting went ok
I/jxcore-log( 7484): 
,D/WifiP2pService(  854): InactiveState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): remove channel information from framework
,I/io.jxcore.node.ConnectionHelper( 7484): onConnectionManagerStateChanged: NOT_STARTED
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7484): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7484): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery stopped successfully
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  854): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service requests cleared successfully
,I/chromium( 7484): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7484): --- start :testSendData.js---
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 0
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): daya100000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): check server
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): serverPort is 50877
I/jxcore-log( 7484): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): initialize: My bluetooth address is B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7484): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7484): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7484): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[153]}
,D/BluetoothSocket( 7484): bindListen(), new LocalSocket 
D/BluetoothSocket( 7484): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7484): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23853816
,D/BluetoothSocket( 7484): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): start: OK
,I/io.jxcore.node.ConnectionHelper( 7484): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7484): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7484): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): start: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7484): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  854): InactiveState{ what=139292 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139292 }
,D/WifiP2pService(  854): P2pEnabledState add service
D/WifiP2pService(  854): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): start: Starting P2P device discovery...
,D/WifiP2pService(  854): InactiveState{ what=139265 }
D/WifiP2pService(  854): P2pEnabledState{ what=139265 }
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  854): callSECApi what=74
D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  854): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7484): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Waiting for incoming connections...
,I/jxcore-log( 7484): StartBroadcasting started ok
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): null
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:46.232Z SendDataTCPServer.js: TCP/IP server is bound to port: 50877
I/jxcore-log( 7484): 
,I/chromium( 7484): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 7484): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7484): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: RESTARTING
,D/WifiP2pService(  854): InactiveState{ what=139268 }
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7484): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery stopped successfully
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  854): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: RESTARTING
,D/WifiP2pService(  854): InactiveState{ what=139268 }
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState add service request
D/WifiP2pManager( 7484): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,I/PowerManagerService(  854): [PWL] Off : 455s ago
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  854): InactiveState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  854): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7484): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 7484): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 7484): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): Found peer : Thali Test (Galaxy A5), Available: true
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): startWithNextDevice
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): device[1]: 7C:F9:0E:51:18:22
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:50.227Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 7484): 
I/jxcore-log( 7484): 2016-01-05T10:26:50.228Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:50.229Z SendDataConnector.js: do connect now
I/jxcore-log( 7484): 
,I/io.jxcore.node.ConnectionHelper( 7484): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 7484): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): connect: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): connect: Started connecting to null in address 7C:F9:0E:51:18:22
,I/io.jxcore.node.ConnectionHelper( 7484): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 1227)
,D/BluetoothUtils( 7484): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7484): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3246): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 7484): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,D/IOP_DB_BT( 3246): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3246): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 3246): db_query_execute: result 1
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): proc btwrite assertion
,E/SMD     (  286): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): Start timer timeout, starting now...
,D/WifiP2pService(  854): InactiveState{ what=139265 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139265 }
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/IOP_DB_BT( 3246): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3246): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3246): db_query_execute: result 1
,W/bt-btif ( 3246): info:x10
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/        ( 3246): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3246): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/WifiP2pService(  854): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-sdp  ( 3246): process_service_search_attr_rsp
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3246): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,D/SecContentProvider(  854): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 3246): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_upio ( 3246): ..proc_btwrite_timeout..
,I/BluetoothBondStateMachine( 3246): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 3246): isSecureModeOn:false
,I/BluetoothBondStateMachine( 3246): Entering PendingCommandState State
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1304): onReceive
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8445): MountEmulatedStorage()
,E/Zygote  ( 8445): v2
I/libpersona( 8445): KNOX_SDCARD checking this for 10099
I/libpersona( 8445): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.common.receiver.AutoLaunchReceiver: pid=8445 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/SELinux ( 8445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8445): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8445): TimaSignature is unavailable
,D/ActivityThread( 8445): Added TimaKeyStore provider
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_upio ( 3246): proc btwrite assertion
,D/btif_config_util( 3246): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3246): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 3246): Failed to remove device: 7C:F9:0E:51:18:22
,D/SecContentProvider(  854): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 3246): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 3246): isSecureModeOn:false
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ResourcesManager( 8445): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/HidService( 3246): getHidService(): returning com.android.bluetooth.hid.HidService@b62fb5
,D/SettingsProvider(  854): name = bluetooth_input_device_priority_7C:F9:0E:51:18:22
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 1002
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/HidService( 3246): Saved priority 7C:F9:0E:51:18:22 = -1
,D/SettingsProvider(  854): name = bluetooth_a2dp_sink_priority_7C:F9:0E:51:18:22
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 1002
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/SettingsProvider(  854): name = bluetooth_headset_priority_7C:F9:0E:51:18:22
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
,D/SettingsProvider(  854): selectionArgs: 1002
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  854): ret = -1
I/BluetoothBondStateMachine( 3246): StableState(): Entering Off State
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,E/[CarMode]( 8445): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 8445): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 8445): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,E/Zygote  ( 8485): MountEmulatedStorage()
E/Zygote  ( 8485): v2
I/libpersona( 8485): KNOX_SDCARD checking this for 10033
I/libpersona( 8485): KNOX_SDCARD not a persona
,I/SELinux ( 8485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  854): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=8485 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 8485): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-btif ( 3246): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3246): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-btif ( 3246): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,E/BluetoothRemoteDevices( 3246): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): onSocketConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1227)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): onBytesWritten: 81 bytes successfully written (thread ID: 1228)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Outgoing connection initialized (*handshake* thread ID: 1228)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Exiting thread (thread ID: 1227)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7484): Entering thread (ID: 1228)
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/TimaKeyStoreProvider( 8485): TimaSignature is unavailable
,D/ActivityThread( 8485): Added TimaKeyStore provider
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): onBytesRead: Read 81 bytes successfully (thread ID: 1228)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Handshake succeeded with [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): onHandshakeSucceeded: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7484): Exiting thread (ID: 1228)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): onConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7484): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/io.jxcore.node.ConnectionHelper( 7484): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 7484): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7484): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 7484): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 7484): Entering thread (ID: 1229)
,D/io.jxcore.node.OutgoingSocketThread( 7484): Server socket local port: 39435
,I/io.jxcore.node.OutgoingSocketThread( 7484): Now accepting connections...
,D/ResourcesManager( 8485): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 8485): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/System.out( 8485): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 8485): Inside WakeupProvider
,E/DatabaseUtils( 8485): Writing exception to parcel
E/DatabaseUtils( 8485): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 8485): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 8485): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 8485): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 8485): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 8485): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 8485): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 8485): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 8485): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 8485): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 8485): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 8445): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/io.jxcore.node.ConnectionHelper( 7484): onListeningForIncomingConnections: Outgoing connection is using port 39435 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 7484): 2016-01-05T10:26:53.335Z SendDataConnector.js: CLIENT connected to 39435, error: null
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:53.336Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7484): 
,W/System.err( 8445): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 8445): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 8445): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 8445): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 8445): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 8445): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 8445): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 8445): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 8445): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 8445): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 8445): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 8445): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 8445): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 8445): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 8445): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 8445): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 8445): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 8445): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8445): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
,W/System.err( 8445): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8445): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8445): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8445): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 8445): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8445): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8445): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/io.jxcore.node.OutgoingSocketThread( 7484): Incoming data from address: /127.0.0.1, port: 39435
D/io.jxcore.node.OutgoingSocketThread( 7484): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7484): setBufferSize: Setting buffer size to 8192 bytes
,I/VlingoApplication( 8485): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
I/io.jxcore.node.StreamCopyingThread( 7484): setBufferSize: Setting buffer size to 8192 bytes
D/io.jxcore.node.StreamCopyingThread( 7484): Entering thread (ID: 1230, name: Sender)
,I/io.jxcore.node.OutgoingSocketThread( 7484): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 7484): Exiting thread (ID: 1229)
,I/jxcore-log( 7484): 2016-01-05T10:26:53.370Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7484): 
,D/io.jxcore.node.StreamCopyingThread( 7484): Entering thread (ID: 1231, name: Receiver)
,E/DatabaseUtils( 8485): Writing exception to parcel
E/DatabaseUtils( 8485): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 8485): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 8485): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 8485): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 8485): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 8485): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 8485): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 8485): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 8485): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 8485): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 8485): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 8445): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 8445): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 8445): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 8445): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 8445): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 8445): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 8445): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 8445): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 8445): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 8445): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 8445): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 8445): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 8445): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 8445): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 8445): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
,W/System.err( 8445): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 8445): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8445): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8445): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8445): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8445): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8445): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8445): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 8445): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8445): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 8445): [DLApplication]-Init Called!:false
,E/[CarMode]( 8445): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 8445): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 8445): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 8445): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 8445): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 8445): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 8445): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 8445): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 8445): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 8445): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 8445): ### android.os.Looper::loop(145)
I/[CarModeFW]( 8445): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 8445): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 8445): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 8445): ### com.android.internal.os.ZygoteInit::main(1194)
,I/VlingoAndroidCore( 8485): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MessageDataHandler( 8445): initialize
,D/[CarModeFW]( 8445): CDH-initiazlieCaches : before sync
,D/[CarModeFW]( 8445): CDH-initiazlieCaches : after sync
,D/VlingoApplication( 8485): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 8485): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/[CarModeFW]( 8445): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 8445): CDH-ContactDataHandler initiazlieCaches time : 28
D/[CarModeFW]( 8445): CDH-initiazlieCaches : end sync
,D/[CarModeFW]( 8445): DrivingManager-initialize...
,I/SensorService(  854): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  854): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  854): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,I/MediaPlayer( 8445): Need to enable context aware info
,V/MediaPlayer-JNI( 8445): native_setup
V/MediaPlayer( 8445): constructor
,V/MediaPlayer( 8445): setListener
,E/MediaPlayer-JNI( 8445): QCMediaPlayer mediaplayer NOT present
,I/art     (  854): Explicit concurrent mark sweep GC freed 65932(4MB) AllocSpace objects, 85(1815KB) LOS objects, 29% free, 38MB/54MB, paused 1.889ms total 159.553ms
,D/[CarModeFW]( 8445): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 8445): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 8445): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarMode]( 8445): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1451989613788
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1451989613790
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1451989613790
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1451989613791
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1451989613792
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1451989613793
,D/[CarModeFW]( 8445): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/SmsProvider( 1467): query,matched:2, calling pid = 8445
,D/TP/SmsProvider( 1467): match 2:Elapsed time : 1.337 ms
,D/MessageDataHandler( 8445):  getInboxList smsCursor : 21
D/TP/SmsProvider( 1467): query,matched:2, calling pid = 8445
,D/TP/SmsProvider( 1467): match 2:Elapsed time : 0.826 ms
,D/TP/MmsProvider( 1467): Query uri=content://mms/inbox, match=2, calling pid = 8445
,D/[CarModeFW]( 8445): RecommendHandler-selection = type = '3'
,D/TP/MmsProvider( 1467): Query uri=content://mms, match=0, calling pid = 8445
,D/[CarModeFW]( 8445): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 8445):  getInboxList mmsCursor : 6
,D/[CarModeFW]( 8445): RecommendHandler-selection = type = '3'
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/MessageDataHandler( 8445): getUnreadMessageCount :0
D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 37
,I/[CarMode]( 8445): [LogNotNull]-Package name is: com.google.android.apps.maps
,E/Zygote  ( 8527): MountEmulatedStorage()
E/Zygote  ( 8527): v2
I/libpersona( 8527): KNOX_SDCARD checking this for 10020
I/libpersona( 8527): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=8527 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/[CarMode]( 8445): [DLApplication]-Init End!:true
,D/[CarModeFW]( 8445): CDH-buildContactCacheWireFrame : cur len =0
,I/SELinux ( 8527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MessageDataHandler( 8445):  getInboxList mms,sms cursor join : 58
,D/TP/MmsSmsProvider( 1467): query,matched:0, calling pid = 8445
,V/TP/MmsSmsProvider( 1467): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1467): match 0:Elapsed time : 1.029 ms
I/SELinux ( 8527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8527): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/SQLiteSecureOpenHelper( 7028): getReadableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 7028): getDatabaseLocked(b,b,pwd)...
D/TP/MmsSmsProvider( 1467): query,matched:13, calling pid = 8445
,D/TP/MmsSmsProvider( 1467): match 13:Elapsed time : 1.100 ms
,D/[CarModeFW]( 8445): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 8445): MyPlaceProvider-=============
D/[CarModeFW]( 8445): MyPlaceProvider-=============
D/[CarModeFW]( 8445): MyPlaceProvider-=============
D/[CarModeFW]( 8445): MyPlaceProvider-=============
D/[CarModeFW]( 8445): MyPlaceProvider----End print all data in content provider---
,D/[CarModeFW]( 8445): MyPlaceProvider-==============
D/[CarModeFW]( 8445): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 8445): MyPlaceProvider-==============
D/[CarModeFW]( 8445): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 8445): MyPlaceProvider-==============
,D/[CarModeFW]( 8445): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 110
,D/MessageDataHandler( 8445):  getInboxList address cursor : 17
,D/TP/MmsSmsProvider( 1467): query,matched:0, calling pid = 8445
,V/TP/MmsSmsProvider( 1467): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1467): match 0:Elapsed time : 1.883 ms
,D/MessageDataHandler( 8445):  getInboxList thread cursor : 6
,D/TimaKeyStoreProvider( 8527): TimaSignature is unavailable
,D/ActivityThread( 8527): Added TimaKeyStore provider
,D/[CarMode]( 8445): [DLApplication]-GooglePlayServices SUCCESS.
,D/MessageDataHandler( 8445):  thread, addr result: 4
I/[CarModeFW]( 8445): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 131
I/[CarModeFW]( 8445): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 131
,E/[CarMode]( 8445): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/ResourcesManager( 8527): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/[CarMode]( 8445): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Thali Test (Galaxy A5) state is 11
,D/[CarModeFW]( 8445): PushMessageService-onCreate
,I/ActivityManager(  854): Killing 7084:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,I/ActivityManager(  854): Killing 7043:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##42
,E/BluetoothHeadset( 7068): BTStateChangeCB is registed
,E/BluetoothHeadset( 7068): BluetoothHeadset service is binded
,D/GMFPReceiver( 7068): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7068): jangil::setProperties()
,D/GMFPReceiver( 7068): jangil::printBTStatus()
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/SettingsProvider(  854): name = Wearable0001
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 10112
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/[CarMode]( 8445): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@d29e7c72, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@db24fc80] LOCATIONS
,D/[CarModeFW]( 8445): PushMessageManager-onServiceConnected
D/[CarModeFW]( 8445): PushMessageService-registerPushMessageServiceListener
W/BackupManagerService(  854): dataChanged but no participant pkg='com.android.providers.settings' uid=10112
,D/GMFPReceiver( 7068): ::::::::Wearable0001::false
,D/SettingsProvider(  854): name = Wearable0002
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
,D/SettingsProvider(  854): selectionArgs: 10112
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
W/BackupManagerService(  854): dataChanged but no participant pkg='com.android.providers.settings' uid=10112
D/GMFPReceiver( 7068): ::::::::Wearable0002::false
,D/GMFPReceiver( 7068): onServiceConnected() : 1
D/GMFPReceiver( 7068): mBluetoothHeadset = true
,I/ActivityManager(  854): Killing 7100:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/BluetoothNotiBroadcastReceiver( 1304): onReceive
,D/[CarMode]( 8445): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Thali Test (Galaxy A5) state is 10
,E/BluetoothHeadset( 7068): BTStateChangeCB is registed
,E/BluetoothHeadset( 7068): BluetoothHeadset service is binded
,D/GMFPReceiver( 7068): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7068): jangil::setProperties()
,W/libprocessgroup(  854): failed to open /acct/uid_10118/pid_7084/cgroup.procs: No such file or directory
,D/GMFPReceiver( 7068): jangil::printBTStatus()
,D/SettingsProvider(  854): name = Wearable0001
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 10112
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
D/GMFPReceiver( 7068): ::::::::Wearable0001::false
,D/SettingsProvider(  854): name = Wearable0002
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 10112
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
D/GMFPReceiver( 7068): ::::::::Wearable0002::false
,D/GMFPReceiver( 7068): onServiceConnected() : 1
,D/GMFPReceiver( 7068): mBluetoothHeadset = true
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 280
,I/[CarModeFW]( 8445): -[snowdeer] Rec : Missed Call : 256
,D/BootupListener( 1467): ACTION_DRIVELINK
,D/SettingsProvider(  854): name = drivelink_navigation
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 1001
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
D/BootupListener( 1467): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  854): name = internet_call_settings_visibility
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 1001
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,I/[CarModeFW]( 8445): -[snowdeer] Rec : Favorite : 20
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_7043/cgroup.procs: No such file or directory
,W/libprocessgroup(  854): failed to open /acct/uid_1000/pid_7100/cgroup.procs: No such file or directory
,I/[CarModeFW]( 8445): -[snowdeer] Rec : CallLog : 4
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8547): MountEmulatedStorage()
E/Zygote  ( 8547): v2
I/libpersona( 8547): KNOX_SDCARD checking this for 10046
I/libpersona( 8547): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=8547 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SELinux ( 8547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,I/SELinux ( 8547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,E/SELinux ( 8547): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/WifiP2pService(  854): InactiveState{ what=139283 }
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/WifiP2pService(  854): DefaultState{ what=139283 }
D/WifiDisplayController(  854): Received list of peers.
D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:,c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService(  854): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService(  854): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/TimaKeyStoreProvider( 8547): TimaSignature is unavailable
,D/ActivityThread( 8547): Added TimaKeyStore provider
,I/ActivityManager(  854): Killing 7138:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ResourcesManager( 8547): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 8547): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/SMD     (  286): DCD ON
,I/CalendarProvider2( 8547): CalendarProvider2.onCreate() called
,W/libprocessgroup(  854): failed to open /acct/uid_10166/pid_7138/cgroup.procs: No such file or directory
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/        ( 3246): PORT_WriteDataCO: tx queue is full,tx.queue_size:10312,tx.queue.count:11,available:24508
I/jxcore-log( 7484): 2016-01-05T10:26:54.426Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7484): 
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_upio ( 3246): ..proc_btwrite_timeout..
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_upio ( 3246): proc btwrite assertion
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:26:54.492Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:26:54.560Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7484): 
,D/        ( 3246): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:14388
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/[CarModeFW]( 8445): -[snowdeer] Rec : Schedule : 544
,I/[CarModeFW]( 8445): -[snowdeer] Rec : During DL app : 2
,I/[CarModeFW]( 8445): -[snowdeer] Rec : Location Sharing : 1
,I/[CarModeFW]( 8445): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 8445): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 8445): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 8445): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 8445): -[snowdeer] Rec : getContactListFromHashMap : 0
,D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 860
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/System.out( 8485): INFO:Resource not found:/Common.properties Using default values
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/[CarModeFW]( 8445): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 8445): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 8445): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 8445): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 886
,I/jxcore-log( 7484): 2016-01-05T10:26:54.702Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/        ( 3246): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:3256
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
I/jxcore-log( 7484): 2016-01-05T10:26:54.767Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
I/jxcore-log( 7484): 2016-01-05T10:26:54.817Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:26:54.846Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:54.850Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:54.948Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:54.953Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:54.954Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): oneRoundDownNow
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:54.960Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:26:54.960Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7484): 
,D/io.jxcore.node.ConnectionHelper( 7484): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,I/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 7484): close
,D/io.jxcore.node.OutgoingSocketThread( 7484): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7484): doStop: Thread ID: 1231
D/io.jxcore.node.OutgoingSocketThread( 7484): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7484): doStop: Thread ID: 1230
D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7484): Either failed to read from the output stream or write to the input stream (thread ID: 1230, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7484): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7484): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7484): closeBluetoothSocketAndStreams
D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@3c22f76d, channel: 6, state: CONNECTED
D/BluetoothSocket( 7484): close() this: android.bluetooth.BluetoothSocket@3c22f76d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d94bfa2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34052433mSocket: android.net.LocalSocket@29aa23f0 impl:android.net.LocalSocketImpl@10049d69 fd:FileDescriptor[154]
D/BluetoothSocket( 7484): Closing mSocket: android.net.LocalSocket@29aa23f0 impl:android.net.LocalSocketImpl@10049d69 fd:FileDescriptor[154]
,D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@3c22f76d, channel: 6, state: CLOSED
D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@3c22f76d, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7484): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7484): Exiting thread (ID: 1230, name: Sender)
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
W/io.jxcore.node.StreamCopyingThread( 7484): Either failed to read from the output stream or write to the input stream (thread ID: 1231, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 7484): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7484): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,E/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7484): Exiting thread (ID: 1231, name: Receiver)
I/jxcore-log( 7484): 2016-01-05T10:26:54.985Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 7484): 
W/bt-btif ( 3246): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): ---- round done--------,
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): startWithNextDevice
I/jxcore-log( 7484): 
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0,
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000,
,D/BatteryService(  854): stay LED for fully charged,
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  854): Plugged
I/MotionRecognitionService(  854): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  854): InactiveState{ what=147477 }
D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService(  854): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService(  854): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,W/ProcessCpuTracker(  854): Skipping unknown process pid 8569
,W/ProcessCpuTracker(  854): Skipping unknown process pid 8572
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 280, CUR = 300
,I/CalendarProvider2( 8547): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8583): MountEmulatedStorage()
,E/Zygote  ( 8583): v2
,I/libpersona( 8583): KNOX_SDCARD checking this for 10149
I/libpersona( 8583): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=8583 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/SELinux ( 8583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8583): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8583): TimaSignature is unavailable
,D/ActivityThread( 8583): Added TimaKeyStore provider
,D/ResourcesManager( 8583): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 8583): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8583): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8609): MountEmulatedStorage()
E/Zygote  ( 8609): v2
I/libpersona( 8609): KNOX_SDCARD checking this for 10150
I/libpersona( 8609): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=8609 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 6747:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8609): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8609): TimaSignature is unavailable
D/ActivityThread( 8609): Added TimaKeyStore provider
,W/libprocessgroup(  854): failed to open /acct/uid_10012/pid_6747/cgroup.procs: No such file or directory
,D/ResourcesManager( 8609): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8609): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager(  854): Killing 7160:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,D/bt_upio ( 3246): ..proc_btwrite_timeout..
,W/libprocessgroup(  854): failed to open /acct/uid_10170/pid_7160/cgroup.procs: No such file or directory
,D/bt_vendor( 3246): op for 7
,D/IOP_DB_BT( 3246): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3246): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3246): db_query_execute: result 1,
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): proc btwrite assertion
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9 vendor_elems=1
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 11 device(s) discovered
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/IOP_DB_BT( 3246): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3246): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 3246): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3246): db_query_execute: result 1
W/bt-btif ( 3246): info:x10
,D/        ( 3246): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3246): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.NAME_CHANGED
,E/SMD     (  286): DCD ON
,E/bt-btm  ( 3246): tBTM_SEC_DEV:0xb3c9000c rs_disc_pending=0
,W/bt-btif ( 3246): bta_dm_check_av:0
,W/bt-btif ( 3246): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1293): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/WifiP2pService(  854): InactiveState{ what=147477 }
,D/WifiP2pService(  854): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  854): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): restart: Restarting...
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/WifiDisplayController(  854): Received list of peers.
,D/WifiDisplayController(  854):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  854):   Device: DIRECT-qjWorkCentre 3025, deviceAddress: 9e:93:4e:3e:3a:c5, primary type: 3-0050F204-5, secondary type: null, wps: 128, grpcapab: 9, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  854):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  854): InactiveState{ what=139283 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139283 }
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/WifiP2pService(  854): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 10: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService(  854): InactiveState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): InactiveState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  854): P2pEnabledState add service request
,D/WifiP2pManager( 7484): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service request added successfully
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3246): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/SecContentProvider(  854): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 3246): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3246): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 3246): isSecureModeOn:false
,I/BluetoothBondStateMachine( 3246): Entering PendingCommandState State
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarModeFW]( 8445): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/BluetoothNotiBroadcastReceiver( 1304): onReceive
,D/[CarMode]( 8445): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 5 state is 11
,E/BluetoothHeadset( 7068): BTStateChangeCB is registed
,E/BluetoothHeadset( 7068): BluetoothHeadset service is binded
,D/GMFPReceiver( 7068): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 7068): jangil::setProperties()
,D/GMFPReceiver( 7068): jangil::printBTStatus()
,D/SettingsProvider(  854): name = Wearable0001
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 10112
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  854): ret = -1
,D/GMFPReceiver( 7068): ::::::::Wearable0001::false
,D/SettingsProvider(  854): name = Wearable0002
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 10112
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  854): ret = -1
D/GMFPReceiver( 7068): ::::::::Wearable0002::false
,D/GMFPReceiver( 7068): onServiceConnected() : 1
,D/GMFPReceiver( 7068): mBluetoothHeadset = true
,D/bt_upio ( 3246): ..proc_btwrite_timeout..
,D/btif_config_util( 3246): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService(  854): InactiveState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  854): P2pEnabledState discover services
,I/BluetoothBondStateMachine( 3246): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3246): Failed to remove device: 34:FC:EF:11:AE:67
,D/SecContentProvider(  854): uri = 4 selection = bluetoothLogForRemote
,E/bt-btm  ( 3246): tBTM_SEC_DEV:0xb3c8fe4c rs_disc_pending=0
,W/bt-btif ( 3246): bta_dm_check_av:0
,W/bt-btif ( 3246): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3246): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 3246): isSecureModeOn:false
,D/HidService( 3246): getHidService(): returning com.android.bluetooth.hid.HidService@b62fb5
,D/WifiService(  854): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/WifiStateMachine(  854): callSECApi what=74
,D/WifiStateMachine(  854): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  854): callSECApiBoolean - ID [13]
,D/SettingsProvider(  854): name = bluetooth_input_device_priority_34:FC:EF:11:AE:67
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
,D/SettingsProvider(  854): selectionArgs: 1002
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/HidService( 3246): Saved priority 34:FC:EF:11:AE:67 = -1
I/wpa_supplicant( 1293): USE_NETWORK : USE_NETWORK OFF
,D/SettingsProvider(  854): name = bluetooth_a2dp_sink_priority_34:FC:EF:11:AE:67
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 1002
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/SettingsProvider(  854): name = bluetooth_headset_priority_34:FC:EF:11:AE:67
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 1002
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,I/BluetoothBondStateMachine( 3246): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service discovery started successfully
,D/BluetoothNotiBroadcastReceiver( 1304): onReceive
,D/[CarMode]( 8445): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 5 state is 10
,E/BluetoothHeadset( 7068): BTStateChangeCB is registed
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_upio ( 3246): proc btwrite assertion
,E/BluetoothHeadset( 7068): BluetoothHeadset service is binded
,D/GMFPReceiver( 7068): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7068): jangil::setProperties()
,D/GMFPReceiver( 7068): jangil::printBTStatus()
,D/SettingsProvider(  854): name = Wearable0001
,D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
,D/SettingsProvider(  854): selectionArgs: 10112
D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  854): ret = -1
,D/GMFPReceiver( 7068): ::::::::Wearable0001::false
,D/SettingsProvider(  854): name = Wearable0002
D/SettingsProvider(  854): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  854): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  854): selectionArgs: false
D/SettingsProvider(  854): selectionArgs: 10112
,D/SecContentProvider(  854): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  854): ret = -1
,D/GMFPReceiver( 7068): ::::::::Wearable0002::false
,D/GMFPReceiver( 7068): onServiceConnected() : 1
,D/GMFPReceiver( 7068): mBluetoothHeadset = true
,I/wpa_supplicant( 1293): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/bt-btm  ( 3246): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 3246): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a44a18
,D/BtConfig.SecureMode( 3246): isSecureModeOn:false
,D/SecContentProvider(  854): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 3246): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW]( 8445): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1304): ACTION_ACL_DISCONNECTED
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/BTConnectionReceiver( 1559): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1559): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-btif ( 3246): new conn_srvc id:26, app_id:255
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-btif ( 3246): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3246): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/BluetoothSocket( 7484): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@222333ee
,E/BluetoothRemoteDevices( 3246): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Incoming connection initialized (thread ID: 1232)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7484): Entering thread (ID: 1232)
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): onBytesRead: Read 66 bytes successfully (thread ID: 1232)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Got valid identity from [34:FC:EF:11:AE:67 Nexus 5]
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): onBytesWritten: 81 bytes successfully written (thread ID: 1232)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): removeThreadFromList: Removing thread with ID 1232
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Handshake thread disposed (thread ID: 1232)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7484): Exiting thread (ID: 1232)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): onConnected: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 7484): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 Nexus 5]
,D/io.jxcore.node.ConnectionHelper( 7484): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 7484): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,I/jxcore-log( 7484): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): Found peer : Nexus 5, Available: true
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): startWithNextDevice
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): device[2]: 34:FC:EF:11:AE:67
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:00.250Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:00.252Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:00.253Z SendDataConnector.js: do connect now
I/jxcore-log( 7484): 
,I/io.jxcore.node.ConnectionHelper( 7484): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 7484): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): connect: [34:FC:EF:11:AE:67 Nexus 5]
,E/SMD     (  286): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): onConnecting: Nexus 5 34:FC:EF:11:AE:67
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 7484): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/io.jxcore.node.ConnectionHelper( 7484): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 Nexus 5], created successfully
,D/io.jxcore.node.ConnectionHelper( 7484): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1233)
,D/io.jxcore.node.IncomingSocketThread( 7484): Entering thread (ID: 1234)
,D/BluetoothUtils( 7484): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7484): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3246): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/BluetoothSocket( 7484): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[155]}
,I/jxcore-log( 7484): 2016-01-05T10:27:00.320Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7484): 
,I/io.jxcore.node.IncomingSocketThread( 7484): Local host address: localhost/127.0.0.1, port: 50877
,D/io.jxcore.node.IncomingSocketThread( 7484): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7484): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7484): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 7484): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 7484): Exiting thread (ID: 1234)
,D/io.jxcore.node.StreamCopyingThread( 7484): Entering thread (ID: 1236, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7484): Entering thread (ID: 1235, name: Sender)
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-sdp  ( 3246): process_service_search_attr_rsp
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-btif ( 3246): new conn_srvc id:26, app_id:1
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,W/bt-btif ( 3246): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3246): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3246): bta_dm_pm_ssr:2, lat:1200,
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,E/BluetoothRemoteDevices( 3246): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): onSocketConnected: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1233)
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): onBytesWritten: 81 bytes successfully written (thread ID: 1237)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Outgoing connection initialized (*handshake* thread ID: 1237)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Exiting thread (thread ID: 1233)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7484): Entering thread (ID: 1237)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): onBytesRead: Read 66 bytes successfully (thread ID: 1237)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7484): Handshake succeeded with [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): onHandshakeSucceeded: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7484): Exiting thread (ID: 1237)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): onConnected: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 7484): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 Nexus 5]
,D/io.jxcore.node.ConnectionHelper( 7484): hasConnection: We have an incoming connection with peer with ID 34:FC:EF:11:AE:67
,W/io.jxcore.node.ConnectionHelper( 7484): onConnected: Already connected with peer [34:FC:EF:11:AE:67 Nexus 5], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 7484): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7484): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 Nexus 5], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 7484): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 7484): Entering thread (ID: 1238)
,D/io.jxcore.node.OutgoingSocketThread( 7484): Server socket local port: 46870
,I/io.jxcore.node.OutgoingSocketThread( 7484): Now accepting connections...
,D/bt_upio ( 3246): ..proc_btwrite_timeout..
,I/io.jxcore.node.ConnectionHelper( 7484): onListeningForIncomingConnections: Outgoing connection is using port 46870 (peer ID: 34:FC:EF:11:AE:67)
,I/jxcore-log( 7484): 2016-01-05T10:27:01.242Z SendDataConnector.js: CLIENT connected to 46870, error: null
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:01.245Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7484): 
,I/io.jxcore.node.OutgoingSocketThread( 7484): Incoming data from address: /127.0.0.1, port: 46870
,D/io.jxcore.node.OutgoingSocketThread( 7484): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7484): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7484): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 7484): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 7484): Exiting thread (ID: 1238)
,D/io.jxcore.node.StreamCopyingThread( 7484): Entering thread (ID: 1239, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 7484): Entering thread (ID: 1240, name: Receiver)
,I/jxcore-log( 7484): 2016-01-05T10:27:01.281Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_upio ( 3246): proc btwrite assertion
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:01.785Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:01.795Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:01.826Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:01.830Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:01.835Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:01.867Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:01.906Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:01.985Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:01.992Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:01.998Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.018Z SendDataTCPServer.js: TCP/IP server has received 53112 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.022Z SendDataTCPServer.js: TCP/IP server has received 55092 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.056Z SendDataTCPServer.js: TCP/IP server has received 59052 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.069Z SendDataTCPServer.js: TCP/IP server has received 61032 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.097Z SendDataTCPServer.js: TCP/IP server has received 63012 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.150Z SendDataTCPServer.js: TCP/IP server has received 64992 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.183Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.257Z SendDataTCPServer.js: TCP/IP server has received 67516 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.367Z SendDataTCPServer.js: TCP/IP server has received 69496 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already,
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/        ( 3246): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:23716
,I/jxcore-log( 7484): 2016-01-05T10:27:02.433Z SendDataTCPServer.js: TCP/IP server has received 83900 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.443Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.446Z SendDataTCPServer.js: TCP/IP server has received 87860 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.454Z SendDataTCPServer.js: TCP/IP server has received 89840 bytes of data
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.459Z SendDataTCPServer.js: TCP/IP server has received 91820 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.465Z SendDataTCPServer.js: TCP/IP server has received 93800 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/        ( 3246): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.523Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.526Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.541Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,W/io.jxcore.node.StreamCopyingThread( 7484): Either failed to read from the output stream or write to the input stream (thread ID: 1236, thread name: Receiver): bt socket closed, read return: -1
,W/bt-btif ( 3246): invalid rfc slot id: 5
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already,
D/bt_vendor( 3246): op for 7,
,D/bt_upio ( 3246): BT_WAKE is asserted already,
,D/        ( 3246): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926,
,E/io.jxcore.node.OutgoingSocketThread( 7484): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 7484): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1234
,D/io.jxcore.node.OutgoingSocketThread( 7484): close: Stopping receiving thread...
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/io.jxcore.node.StreamCopyingThread( 7484): doStop: Thread ID: 1236
,D/io.jxcore.node.OutgoingSocketThread( 7484): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7484): doStop: Thread ID: 1235
D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7484): Either failed to read from the output stream or write to the input stream (thread ID: 1235, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7484): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7484): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7484): closeBluetoothSocketAndStreams
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@1ae3d08f, channel: 6, state: CONNECTED
,D/BluetoothSocket( 7484): close() this: android.bluetooth.BluetoothSocket@1ae3d08f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a258f1c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f40a725mSocket: android.net.LocalSocket@d12a0fa impl:android.net.LocalSocketImpl@3956e6ab fd:FileDescriptor[152]
D/BluetoothSocket( 7484): Closing mSocket: android.net.LocalSocket@d12a0fa impl:android.net.LocalSocketImpl@3956e6ab fd:FileDescriptor[152]
,D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@1ae3d08f, channel: 6, state: CLOSED
,D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@1ae3d08f, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7484): Exiting thread (ID: 1235, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 7484): Exiting thread (ID: 1236, name: Receiver)
,I/jxcore-log( 7484): 2016-01-05T10:27:02.650Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.653Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.693Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.762Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7484): 
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,I/jxcore-log( 7484): 2016-01-05T10:27:02.842Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.872Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.878Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): oneRoundDownNow
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.884Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): 2016-01-05T10:27:02.887Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7484): 
,D/io.jxcore.node.ConnectionHelper( 7484): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
,I/io.jxcore.node.OutgoingSocketThread( 7484): close
,D/io.jxcore.node.OutgoingSocketThread( 7484): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7484): doStop: Thread ID: 1240
,D/io.jxcore.node.OutgoingSocketThread( 7484): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7484): doStop: Thread ID: 1239,
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing...,
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the local input stream...,
,W/io.jxcore.node.StreamCopyingThread( 7484): Either failed to read from the output stream or write to the input stream (thread ID: 1239, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7484): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 7484): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 7484): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 7484): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@378a8108, channel: 5, state: CONNECTED
,D/BluetoothSocket( 7484): close() this: android.bluetooth.BluetoothSocket@378a8108, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d7990a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2459d2c6mSocket: android.net.LocalSocket@239b4287 impl:android.net.LocalSocketImpl@32caa5b4 fd:FileDescriptor[155]
,D/BluetoothSocket( 7484): Closing mSocket: android.net.LocalSocket@239b4287 impl:android.net.LocalSocketImpl@32caa5b4 fd:FileDescriptor[155]
,W/io.jxcore.node.StreamCopyingThread( 7484): Either failed to read from the output stream or write to the input stream (thread ID: 1240, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 7484): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 7484): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@378a8108, channel: 5, state: CLOSED
D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@378a8108, channel: 5, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7484): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7484): Exiting thread (ID: 1239, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 7484): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7484): Exiting thread (ID: 1240, name: Receiver)
,I/jxcore-log( 7484): 2016-01-05T10:27:02.946Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): ---- round done--------
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): startWithNextDevice
I/jxcore-log( 7484): 
,W/bt-btif ( 3246): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/bt_vendor( 3246): op for 7
D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): BT_WAKE is asserted already
,E/SMD     (  286): DCD ON
,D/bt_upio ( 3246): ..proc_btwrite_timeout..
,D/bt_vendor( 3246): op for 7
,D/BatteryService(  854): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  854): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  854): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  854):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  854): Plugged
,I/MotionRecognitionService(  854): setPowerConnected  = true
,D/BatteryService(  854): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1174):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3246): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3246): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  854): SIOP:: AP = 290, PST = 280, CUR = 300
,E/SMD     (  286): DCD ON
,I/jxcore-log( 7484): teardown
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): testSendData stopped
I/jxcore-log( 7484): 
,I/io.jxcore.node.ConnectionHelper( 7484): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): shutdown
,D/BluetoothSocket( 7484): close() in, this: android.bluetooth.BluetoothSocket@3bfd95dd, channel: 6, state: LISTENING
,D/BluetoothSocket( 7484): close() this: android.bluetooth.BluetoothSocket@3bfd95dd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23853816, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14905552mSocket: android.net.LocalSocket@adf8023 impl:android.net.LocalSocketImpl@38466920 fd:FileDescriptor[153]
,D/BluetoothSocket( 7484): Closing mSocket: android.net.LocalSocket@adf8023 impl:android.net.LocalSocketImpl@38466920 fd:FileDescriptor[153]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7484): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7484): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7484): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7484): stop: Stopping services
,D/WifiP2pService(  854): InactiveState{ what=139298 }
,D/WifiP2pService(  854): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  854): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): onIsWifiPeerDiscoveryStartedChanged: false
,D/WifiP2pService(  854): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7484): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): release: The given listener does not exist in the list
,I/wpa_supplicant( 1293): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7484): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7484): setState: NOT_STARTED
,I/jxcore-log( 7484): StopBroadcasting went ok
I/jxcore-log( 7484): 
,D/WifiP2pService(  854): InactiveState{ what=139307 }
,I/jxcore-log( 7484): 2016-01-05T10:27:06.538Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7484): 
,D/WifiP2pService(  854): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  854): P2pEnabledState clear service request
,D/WifiP2pService(  854): remove channel information from framework
,D/WifiP2pService(  854): InactiveState{ what=147493 }
,I/jxcore-log( 7484): 2016-01-05T10:27:06.550Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7484): 
,D/WifiP2pService(  854): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  854): discovery change broadcast false
,I/io.jxcore.node.ConnectionHelper( 7484): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7484): Local services cleared successfully
,I/io.jxcore.node.ConnectionHelper( 7484): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7484): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7484): Service requests cleared successfully
,I/chromium( 7484): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7484): ****TEST TOOK:  ms ****
I/jxcore-log( 7484): 
,I/jxcore-log( 7484): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7484): 
,D/TimaService(  854): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  854): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService(  854): TimaServiceHandler.handleMessage what =1
,D/bt_vendor( 3246): op for 7
,D/bt_upio ( 3246): proc btwrite assertion
,D/AndroidRuntime( 8678): 
D/AndroidRuntime( 8678): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8678): CheckJNI is OFF
,D/AndroidRuntime( 8678): setted country_code = Germany
,D/AndroidRuntime( 8678): setted countryiso_code = DE
,D/AndroidRuntime( 8678): setted sales_code = DBT
,D/AndroidRuntime( 8678): readGMSProperty: start
D/AndroidRuntime( 8678): readGMSProperty: already setted!!
,D/AndroidRuntime( 8678): readGMSProperty: end
D/AndroidRuntime( 8678): addProductProperty: start
,E/bt-btm  ( 3246): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 3246): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1174): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/[CarModeFW]( 8445): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,V/BluetoothEventManager( 1304): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1304): ACTION_ACL_DISCONNECTED
,D/BluetoothAdapterService( 3246): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a44a18
D/BtConfig.SecureMode( 3246): isSecureModeOn:false
D/SecContentProvider(  854): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 3246): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1174): isGear1: device is not B1!
,I/BTConnectionReceiver( 1559): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1559): Bluetooth Device Name: Nexus 5
,E/AffinityControl( 8678): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8678): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  854): START PACKAGE DELETE: observer{709554547}
D/PackageManager(  854): pkg{<packageName>}
D/PackageManager(  854): user{0}
D/PackageManager(  854): caller{2000}
D/PackageManager(  854): flags{3}
,D/PersonaManagerService(  854): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  854): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  854): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  854): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  854): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  854): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  854): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  854): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  854): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  854): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  854): !@killApplicatoin: 10367, uninstall pkg
,I/ActivityManager(  854): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
,I/ActivityManager(  854): Killing 7484:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
,I/ActivityManager(  854):   Force finishing activity ActivityRecord{cc9b37c u0 com.test.thalitest/.MainActivity t12}
,D/FocusedStackFrame(  854): Set to : 0
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,W/PackageSettings(  854): Skipping PackageSetting{16be10fd com.example.hello/10375} due to missing metadata
,I/ActivityManager(  854): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
,D/ConnectivityService(  854): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiService(  854): Client connection lost with reason: 4
,I/art     ( 4419): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 333us total 31.358ms
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 1559): Explicit concurrent mark sweep GC freed 8774(364KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 16MB/27MB, paused 3.105ms total 87.263ms
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/SamsungIME( 1884): mOCRHelper is null
,E/libprocessgroup(  854): failed to kill 1 processes for processgroup 7484
,I/InputReader(  854): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 2194): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.503: ( 7665): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7665): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1451989627707
,I/KLMS-2.4.503: ( 7665): MainReciver(): PACKAGE_REMOVED
,I/art     (  854): Explicit concurrent mark sweep GC freed 29906(2MB) AllocSpace objects, 10(160KB) LOS objects, 29% free, 38MB/54MB, paused 7.624ms total 175.939ms
I/art     (  854): WaitForGcToComplete blocked for 55.757ms for cause Explicit
D/ResourcesManager(  854): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/KLMS-2.4.503: ( 7665): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/RegisteredServicesCache( 1460): empty dynamic service
,D/SecContentProvider2(  854): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  854): mCursor = null
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/EnterpriseDeviceManagerService(  854): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  854): Admin package name: com.google.android.gms
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
E/Zygote  ( 8708): MountEmulatedStorage()
E/Zygote  ( 8708): v2
I/libpersona( 8708): KNOX_SDCARD checking this for 10104
I/libpersona( 8708): KNOX_SDCARD not a persona
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ActivityManager(  854): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8708 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/SELinux ( 8708): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8708): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8708): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/TimaKeyStoreProvider( 8708): TimaSignature is unavailable
,D/ActivityThread( 8708): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     (  854): Explicit concurrent mark sweep GC freed 10163(479KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 38MB/54MB, paused 4.422ms total 238.823ms
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/SurfaceWidgetView( 1490): destroyHardwareResources():1068219464
,D/ResourcesManager( 8708): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,V/WindowOrientationListener(  854): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  854): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  854): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  854): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  854): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/Launcher( 1490): onRestart, Launcher: 156117719
,D/Launcher( 1490): onStart, Launcher: 156117719
D/Launcher.HomeView( 1490): onStart
,D/elm:14451( 8708): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/elm:14451( 8708): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8708): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8708): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2258): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2258): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  854): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/StatusBarManagerService(  854): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1174): value : false
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/elm:14451( 8708): ElmAgentService : onCreate()
,E/Zygote  ( 8726): MountEmulatedStorage()
E/Zygote  ( 8726): v2
I/libpersona( 8726): KNOX_SDCARD checking this for 10017
I/libpersona( 8726): KNOX_SDCARD not a persona
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/ActivityManager(  854): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8726 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/elm:14451( 8708): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/elm:14451( 8708): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8708): MDMBridge.getInstance()
,D/elm:14451( 8708): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 8726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/elm:14451( 8708): MDMBridge.getAllLicenseInfoFromSDK()
,E/SELinux ( 8726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputMethodManagerService(  854): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  854): Got RemoteException sending setActive(false) notification to pid 7484 uid 10367
,D/PackageManager(  854): delete codoeFile: 
,W/ContextImpl(  854): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager(  854): result of delete: 1{709554547}
,D/TimaKeyStoreProvider( 8726): TimaSignature is unavailable
,D/ActivityThread( 8726): Added TimaKeyStore provider
,D/ResourcesManager(  854): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/RCPManagerService(  854): PackageReceiver onReceive()
I/HarmonyEASService(  854): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ResourcesManager( 8726): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/KnoxMUMContainerPolicy(  854): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:14451( 8708): ElmAgentService : onDestroy().
,I/ActivityManager(  854): Killing 6273:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,D/BackupManagerService(  854): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/AndroidRuntime( 8678): Shutting down VM
,D/JobSchedulerService(  854): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,V/EnterpriseBillingPolicy(  854): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  854): uID is 10367
V/EnterpriseBillingPolicy(  854): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  854): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  854): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  854): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  854): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  854): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  854): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  854): removeObsoleteFile: deleting file=12_task.xml
,D/TaskPersister(  854): removeObsoleteFile: deleting file=12_task_thumbnail.png
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,I/Timeline(  854): Timeline: Activity_windows_visible id: ActivityRecord{3329886c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:612641
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8726): onReceive()
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8726): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8726): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 6816): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6816): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6816): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6816): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/LockPatternUtilsCache( 1174): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1174): value : false
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  ( 8744): MountEmulatedStorage()
E/Zygote  ( 8744): v2
I/libpersona( 8744): KNOX_SDCARD checking this for 10034
I/libpersona( 8744): KNOX_SDCARD not a persona
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/ActivityManager(  854): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8744 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  854): Killing 7237:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     (  312): Explicit concurrent mark sweep GC freed 8709(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 14.535ms
I/SELinux ( 8744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8744): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  854): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.222ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 8.442ms
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 8744): TimaSignature is unavailable
,D/ActivityThread( 8744): Added TimaKeyStore provider
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/libprocessgroup(  854): failed to open /acct/uid_10114/pid_6273/cgroup.procs: No such file or directory
,W/libprocessgroup(  854): failed to open /acct/uid_10044/pid_7237/cgroup.procs: No such file or directory
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  854): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/FeatureConfig( 8744): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  854): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  854): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  854): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  854): clearDefaults: com.test.thalitest
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/CrashAnrDetector(  854): onPackageRemoved : com.test.thalitest
,W/ResourcesManager( 8744): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/bt_vendor( 3246): op for 7
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8744): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8744): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8744): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SharedPreferencesImpl( 8744): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/EventHub(  854): Removing device '/dev/input/event4' due to inotify event
,I/ActivityManager(  854): Process com.samsung.android.app.galaxyfinder (pid 8744)(adj 0) has died(161,554)
,I/EventHub(  854): Removing device '/dev/input/event5' due to inotify event
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,I/TLC_TIMA_PKM_measure_kernel(  854): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  854): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,I/Zygote  (  312): Process 8744 exited due to signal (7)
,E/Zygote  ( 8766): MountEmulatedStorage()
I/libpersona( 8766): KNOX_SDCARD checking this for 10035
E/Zygote  ( 8766): v2
I/libpersona( 8766): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8766 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/TimaService(  854): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  854): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/EventHub(  854): Removing device '/dev/input/event6' due to inotify event
,I/SELinux ( 8766): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,I/EventHub(  854): Removing device '/dev/input/event7' due to inotify event
,E/SELinux ( 8766): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8766): TimaSignature is unavailable
,D/ActivityThread( 8766): Added TimaKeyStore provider
,I/EventHub(  854): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager( 8766): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 8766): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
,E/ActivityThread( 8766): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8766): Zip: failed reading lfh name from offset 418254
,D/AndroidRuntime( 8766): Shutting down VM
,E/audit_log( 2095): File locking failed. error= Bad file number
,D/bt_upio ( 3246): ..proc_btwrite_timeout..
,I/EventHub(  854): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager(  854): Process com.sec.android.app.shealth (pid 8766)(adj 0) has died(160,554)
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/ActivityManager(  854): Process com.sec.spp.push (pid 5117)(adj 0) has died(166,554)
,I/Zygote  (  312): Process 8766 exited due to signal (7)
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
I/EventHub(  854): Removing device '/dev/input/event10' due to inotify event
,I/Zygote  (  312): Process 5117 exited due to signal (7)
,E/Zygote  ( 8785): MountEmulatedStorage()
E/Zygote  ( 8785): v2
I/libpersona( 8785): KNOX_SDCARD checking this for 10038
I/libpersona( 8785): KNOX_SDCARD not a persona
,I/ActivityManager(  854): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8785 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub(  854): Removing device '/dev/input/event11' due to inotify event
,E/Watchdog(  854): !@Sync 20
,I/SELinux ( 8785): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8785): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8785): TimaSignature is unavailable
,D/ActivityThread( 8785): Added TimaKeyStore provider
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/ResourcesManager( 8785): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8785): Unable to create files subdir /data/data/com.sec.spp.push/cache
,E/ActivityThread( 8785): Unable to setupGraphicsSupport due to missing cache directory
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/ActivityManager(  854): Process com.sec.spp.push:RemoteNotiProcess (pid 8785)(adj 0) has died(166,555)
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  854): checkUser: useridlist=null, currentuser=0

```
