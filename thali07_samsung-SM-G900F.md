#### Test 50650278e3ff7c2_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
E/SMD     (  280): DCD ON
I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7318): null auth token
I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
W/ApiaryClient( 7318): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8839328148975116373&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
--------- beginning of system
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
D/AndroidRuntime( 7365): 
D/AndroidRuntime( 7365): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7365): CheckJNI is OFF
D/AndroidRuntime( 7365): setted country_code = Germany
D/AndroidRuntime( 7365): setted countryiso_code = DE
D/AndroidRuntime( 7365): setted sales_code = DBT
D/AndroidRuntime( 7365): readGMSProperty: start
D/AndroidRuntime( 7365): readGMSProperty: already setted!!
D/AndroidRuntime( 7365): readGMSProperty: end
D/AndroidRuntime( 7365): addProductProperty: start
E/AffinityControl( 7365): AffinityControl: registerfunction enter
D/AndroidRuntime( 7365): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  873): inState():  stateMachine is null !!
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  873): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  873): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  873): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  873): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/AndroidRuntime( 7365): Shutting down VM
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 25
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  873): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 873) 
D/LightsService(  873): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  873): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  873): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/PhoneStatusBar( 1167): Icon Only
D/WindowManager(  873): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
V/BitmapFactory( 1167): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7387): MountEmulatedStorage()
E/Zygote  ( 7387): v2
I/libpersona( 7387): KNOX_SDCARD checking this for 10367
I/libpersona( 7387): KNOX_SDCARD not a persona
V/BitmapFactory( 1167): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/ActivityManager(  873): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7387 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/BooksSync( 7318): Soft error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8839328148975116373&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7318): Sync error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8839328148975116373&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7318): Finished books sync
I/SELinux ( 7387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/KnoxNotification( 1167): ----- inflateViews : modified publicViewLocal -----
E/SELinux ( 7387): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66337, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  873): Killing 6313:com.google.android.talk/u0a117 (adj 15): bgCount ##41
D/KnoxNotification( 1167): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1167): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1167): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@10872ac
D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1167): Icon Only
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/TimaKeyStoreProvider( 7387): TimaSignature is unavailable
D/ActivityThread( 7387): Added TimaKeyStore provider
V/ActivityManager(  873): Display changed displayId=0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBarManagerService(  873): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/ResourcesManager( 7387): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/libprocessgroup(  873): failed to open /acct/uid_10117/pid_6313/cgroup.procs: No such file or directory
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PowerManagerService(  873): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1167 (0x0)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/WebViewFactory( 7387): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7387): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/LibraryLoader( 7387): Loading: webviewchromium
,I/LibraryLoader( 7387): Time to load native libraries: 2 ms (timestamps 6686-6688)
,I/LibraryLoader( 7387): Expected native library version number "",actual native library version number ""
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,V/WebViewChromiumFactoryProvider( 7387): Binding Chromium to main looper Looper (main, tid 1) {26dc9d99}
,I/LibraryLoader( 7387): Expected native library version number "",actual native library version number ""
I/chromium( 7387): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7387): Initializing chromium process, renderers=0
,W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/chromium( 7387): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7387): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7387): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/Adreno-EGL( 7387): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7387): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7387): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7387): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7387): Remote Branch: 
I/Adreno-EGL( 7387): Local Patches: 
I/Adreno-EGL( 7387): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,W/chromium( 7387): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7387): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7387): onDetachedFromWindow called when already detached. Ignoring
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/SystemWebViewEngine( 7387): CordovaWebView is running on device made by: samsung
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7387): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/Activity( 7387): performCreate Call secproduct feature valuefalse
D/Activity( 7387): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/OpenGLRenderer( 7387): Render dirty regions requested: true
,D/ActivityManager(  873): post active user change for 0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/KnoxTimeoutHandler(  873): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  873): handleActiveUserChange for user 0
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/OpenGLRenderer( 7387): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7387): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7387): Enabling debug mode 0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/InputMethodManagerService(  873): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Adreno-ES20( 7387): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7387): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  873): Displayed com.test.thalitest/.MainActivity: +666ms
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/GAV2    ( 7318): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/Timeline( 7387): Timeline: Activity_idle id: android.os.BinderProxy@29e12810 time:97111
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,V/AlarmManager(  873): waitForAlarm result :4
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/JsMessageQueue( 7387): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/chromium( 7387): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7387): 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/CustomFrequencyManagerService(  873): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  873): mDVFSHelper.release()
I/Timeline(  873): Timeline: Activity_windows_visible id: ActivityRecord{6525e32 u0 com.test.thalitest/.MainActivity t12} time:97274
,D/CustomFrequencyManagerService(  873): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/jxcore_app_log( 7387): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358533504
,D/JX-Cordova( 7387): jxcore cordova android initializing
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/SSRM:m  (  873): SIOP:: AP = 360, PST = 427, CUR = 300
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 2.
,D/CustomFrequencyManagerService(  873): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  tag : ACTIVITY_RESUME_BOOSTER@10
,E/SMD     (  280): DCD ON
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,W/jxcore-log( 7387): Initializing JXcore engine
,W/jxcore-log( 7387): JXcore engine is ready
,W/jxcore-log( 7387): Starting JXcore engine
,E/auditd  ( 2171): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  873): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  873): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7453): MountEmulatedStorage()
,E/Zygote  ( 7453): v2
I/libpersona( 7453): KNOX_SDCARD checking this for 1000
I/libpersona( 7453): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7453 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7453): TimaSignature is unavailable
,D/ActivityThread( 7453): Added TimaKeyStore provider
,W/jxcore-log( 7387): Platform android
W/jxcore-log( 7387): 
W/jxcore-log( 7387): Process ARCH arm
W/jxcore-log( 7387): 
,D/ResourcesManager( 7453): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7453):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7453):  SeDenialReceiver : File path = null
,I/ActivityManager(  873): Killing 6558:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,W/libprocessgroup(  873): failed to open /acct/uid_10075/pid_6558/cgroup.procs: No such file or directory
,I/jxcore-log( 7387): JXcore Cordova bridge is ready!
I/jxcore-log( 7387): 
,W/jxcore-log( 7387): JXcore engine is started
I/Choreographer( 7387): Skipped 128 frames!  The application may be doing too much work on its main thread.
,D/TaskPersister(  873): removeObsoleteFile: deleting file=11_task_thumbnail.png
,I/jxcore-log( 7387): Toggling radios to true
I/jxcore-log( 7387): 
,D/BluetoothAdapter( 7387): enable()
,D/BluetoothAdapter( 7387): enable(): BT is already enabled..!
,D/WifiService(  873): New client listening to asynchronous messages
,I/WifiManager( 7387): packageName : com.test.thalitest
,D/SecContentProvider(  873): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  873): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  873): mCursor = null
,D/WifiService(  873): setWifiEnabled: true pid=7387, uid=10367
E/WifiService(  873): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  873): Permission Denial: getCurrentUser() from pid=7387, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  873): Failed getting userId using ActivityManagerNative
W/WifiService(  873): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7387, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  873): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  873): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  873): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  873): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  873): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  873): name = wifi_on
,I/WifiService(  873): disconnect: pid=7387, uid=10367
,I/wpa_supplicant( 1280): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7387): Radios toggled
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): Perf Test app loaded loaded
I/jxcore-log( 7387): 
,I/jxcore-log( 7387): check test folder
I/jxcore-log( 7387): 
,I/wpa_supplicant( 1280): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1280): wlan0: State: COMPLETED -> DISCONNECTED
,I/jxcore-log( 7387): found test : ./testFindPeers.js
I/jxcore-log( 7387): 
,I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  873): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1280): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1280): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1280): Disconnected - do not scan
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  873): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  873): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  873): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  873): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/PowerManagerService(  873): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  873): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  873): [s] DisplayPowerCallbacks : onStateChanged()
,E/WifiStateMachine(  873): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  873): InactiveState{ what=143375 }
,D/WifiP2pService(  873): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/lights  (  873): lcd : 24 +
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/lights  (  873): lcd : 24 -
,I/jxcore-log( 7387): found test : ./testSendData.js
I/jxcore-log( 7387): 
,D/lights  (  873): lcd : 16 +
,V/NativeCrypto( 1674): Read error: ssl=0xaf281e00: I/O error during system call, Connection timed out
,D/DisplayPowerController(  873): getFinalBrightness : 15 -> 15
,D/lights  (  873): lcd : 16 -
,D/lights  (  873): lcd : 15 +
,V/NativeCrypto( 1674): SSL shutdown failed: ssl=0xaf281e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  873): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  873): updateNetworkInfo()
,D/ConnectivityService(  873): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/SMD     (  280): DCD ON
E/ConnectivityService(  873): updateNetworkInfo()
,D/ConnectivityService(  873): ignoring duplicate network state non-change
D/ConnectivityService(  873): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  873): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/lights  (  873): lcd : 15 -
,D/DisplayPowerController(  873): getFinalBrightness : 15 -> 15
,I/WifiTrafficPoller(  873): evaluateTrafficStatsPolling
,I/CLocInfoService(  873): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/WifiStateMachine(  873): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1280): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1280): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1280): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1280): First Scan Start
,I/wpa_supplicant( 1280): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  873): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  873): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  873): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  873): InactiveState{ what=143375 }
D/WifiP2pService(  873): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): Validated
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/Hs20UtilService( 1300): Starting #6
,I/Hs20UtilService( 1300): Message received 5007
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  873): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  873): calling update connectivity
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  873): Not allowed due to - mEnabled false
E/WifiStateMachine(  873): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  873): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524292
D/WifiStateMachine(  873): updateConfiguredNetworkExpiration - currTime: 1450100295942
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiStateMachine(  873): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
I/WifiTrafficPoller(  873): evaluateTrafficStatsPolling
D/ConnectivityService(  873): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  873): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  873): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  873): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1461): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  873): NetworkAgent: NetworkAgent channel lost
D/CSLegacyTypeTracker(  873): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  873): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
I/CLocInfoService(  873): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
E/WifiStateMachine(  873): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  873): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
E/WifiStateMachine(  873): setDetailed state send new extra info"NG700"
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService(  873): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  873): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  873): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
,V/NetworkStats(  873): updateIfacesLocked()
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
V/NetworkStats(  873): performPollLocked(flags=0x1)
D/SmartBondingService(  873): getNetworkEnabled : wifi : true mobile : true
D/NetworkStatsFactory(  873): UpdateStatsForKnox
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1167): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1167): updateDataNetType()
D/StatusBar.NetworkController( 1167): NoService, mRoamingIconId = 0
E/ConnectivityService(  873): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  873): performPollLocked() took 6ms
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
V/NetworkStats(  873): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1167): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/SecContentProvider2(  873): uri = 20 selection = getPromptCredentialsEnabled
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/SecContentProvider2(  873): mCursor = null
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/SecContentProvider2(  873): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  873): mCursor = null
I/Hs20UtilService( 1300): Starting #7
I/Hs20UtilService( 1300): Message received 5007
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,I/Choreographer( 7387): Skipped 74 frames!  The application may be doing too much work on its main thread.
D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,I/chromium( 7387): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,I/chromium( 7387): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  873): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  873): MasterInitialState.processMessage what=3
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  873): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  873): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  873): CLoinfo wifi false
,D/SmartBondingService(  873): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  873): getNetworkEnabled : wifi : true mobile : true
,I/ApplicationPolicy(  873): updateDataUsageMap
,I/SystemBroadcastReceiver( 7155): [#DCM#] [DCM_Performance] onReceive completed in time  3149 microsec. 
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7155): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7155): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/SLocation(  873): No Active Data Connection
,I/DBG_DM  ( 3819): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5389): type=WIFI subType= reason=null isConnected=false
,I/DCMController( 7155): [#DCM#] setIsConnectedForExtractors 
,I/PCWCLIENTTRACE_PushUtil( 6773): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6773): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6773): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6773): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6773): noConnectivity : true
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3819): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7510): MountEmulatedStorage()
,E/Zygote  ( 7510): v2
I/libpersona( 7510): KNOX_SDCARD checking this for 10002
I/libpersona( 7510): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7510 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  310): Explicit concurrent mark sweep GC freed 8742(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 265us total 14.621ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 8.393ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 8.809ms
,D/TimaKeyStoreProvider( 7510): TimaSignature is unavailable
,D/ActivityThread( 7510): Added TimaKeyStore provider
,D/ResourcesManager( 7510): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  873): Killing 6581:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7536): MountEmulatedStorage()
E/Zygote  ( 7536): v2
I/libpersona( 7536): KNOX_SDCARD checking this for 1000
I/libpersona( 7536): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7536 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7536): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7536): TimaSignature is unavailable
,D/ActivityThread( 7536): Added TimaKeyStore provider
,D/ResourcesManager( 7536): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_6581/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7536): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7536): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7536): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7536): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7536): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7536): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7554): MountEmulatedStorage()
,E/Zygote  ( 7554): v2
I/libpersona( 7554): KNOX_SDCARD checking this for 10011
I/libpersona( 7554): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7554 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7554): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7554): TimaSignature is unavailable
,D/ActivityThread( 7554): Added TimaKeyStore provider
,D/ResourcesManager( 7554): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  873): Killing 6615:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7554): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7554): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1280): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 1280): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1280): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1280): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  873): [1,450,100,296,997 ms] noteScanEnd no scan source
,E/WifiStateMachine(  873): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@93b74e9 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  873): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  873): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  873): setDetailed state send new extra info0x
,D/SecContentProvider2(  873): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  873): mCursor = null
,I/CLocInfoService(  873): External Intent Received android.net.wifi.SCAN_RESULTS
,I/FOTA_Client( 7554): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7554): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7554): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7574): MountEmulatedStorage()
I/libpersona( 7574): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7574): v2
I/libpersona( 7574): KNOX_SDCARD not a persona
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_6615/cgroup.procs: No such file or directory
,I/ActivityManager(  873): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7574 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  873): Killing 6736:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7574): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  873): failed to open /acct/uid_10015/pid_6736/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7574): TimaSignature is unavailable
D/ActivityThread( 7574): Added TimaKeyStore provider
,D/ResourcesManager( 7574): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/wpa_supplicant( 1280): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1280): Associated with C0.AA.48
E/WifiStateMachine(  873): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  873): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  873): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  873): mCursor = null
,I/KLMS-2.4.503: ( 7574): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7574): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450100297109
,I/KLMS-2.4.503: ( 7574): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7574): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7574): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  873): Killing 6756:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/wpa_supplicant( 1280): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  873): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  873): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  873): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  873): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  873): mCursor = null
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1280): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1280): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1280): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/ActivityManager(  873): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7589 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
I/wpa_supplicant( 1280): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1280): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1280): Blacklist: Clear (temp) 
I/wpa_supplicant( 1280): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/Zygote  ( 7589): MountEmulatedStorage()
I/libpersona( 7589): KNOX_SDCARD checking this for 10037
E/Zygote  ( 7589): v2
I/libpersona( 7589): KNOX_SDCARD not a persona
,E/WifiStateMachine(  873): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  873): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  873): Network connection established
,D/WifiNative-HAL(  873): callSECApiVoid - ID [50]
E/WifiStateMachine(  873): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  873): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  873): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  873): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  873): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  873): Got NetworkAgent Messenger
E/ConnectivityService(  873): updateNetworkInfo()
D/ConnectivityService(  873): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine(  873): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  873): NetworkAgent connected
E/WifiStateMachine(  873): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  873): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SELinux ( 7589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7589): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  873): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  873): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  873): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  873): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/libprocessgroup(  873): failed to open /acct/uid_10016/pid_6756/cgroup.procs: No such file or directory
,D/CommandListener(  275): Setting iface cfg
,E/WifiStateMachine(  873): Start Dhcp Watchdog 2
,D/SecContentProvider2(  873): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  873): mCursor = null
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  873): calculateWifiScore() report new score 60
I/WifiStateMachine(  873): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  873): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,E/WifiStateMachine(  873): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  873): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  873): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
D/ConnectivityService(  873): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7589): TimaSignature is unavailable
,D/ActivityThread( 7589): Added TimaKeyStore provider
,D/ResourcesManager( 7589): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7589): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5152): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6811): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6811): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6811): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6811): [SLFUCHKMGR] constructor called
,I/SA      ( 6811): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6811): [OR] == isSIMCardReady false ==
,I/SA      ( 6811): [SCU] == networkStateCheck == false
I/SA      ( 6811): [OR] onReceive END
,E/SPPClientService( 5152): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  873): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  873): do suspend false
,D/WifiP2pService(  873): InactiveState{ what=143375 }
,D/WifiP2pService(  873): P2pEnabledState{ what=143375 }
,D/SecContentProvider2(  873): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  873): mCursor = null
,E/Zygote  ( 7611): MountEmulatedStorage()
E/Zygote  ( 7611): v2
I/libpersona( 7611): KNOX_SDCARD checking this for 10071
I/libpersona( 7611): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7611 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  873): Killing 6529:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7611): TimaSignature is unavailable
,D/ActivityThread( 7611): Added TimaKeyStore provider
,D/ResourcesManager( 7611): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7611): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7611): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7611): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup(  873): failed to open /acct/uid_10034/pid_6529/cgroup.procs: No such file or directory
,D/comsamsunglog( 7611): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7611): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7611): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7611): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7611): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7611): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7611): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7611): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  873): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  873): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  873): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  873): selectionArgs: false
D/SettingsProvider(  873): selectionArgs: 10071
D/SecContentProvider(  873): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  873): ret = -1
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7611): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7611): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7611): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7611): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7611): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7611): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7611): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7611): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7611): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7611): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7629): MountEmulatedStorage()
E/Zygote  ( 7629): v2
I/libpersona( 7629): KNOX_SDCARD checking this for 1000
I/libpersona( 7629): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7629 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  873): Killing 4640:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  873): failed to open /acct/uid_10035/pid_4640/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7629): TimaSignature is unavailable
,D/ActivityThread( 7629): Added TimaKeyStore provider
,D/ResourcesManager( 7629): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7629): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7629): premStatus:2
,I/KnoxUsageLogPro( 7629): isEulaShown : false
,I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive : not Processible, just return
,E/dhcpcd  ( 7647): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7647): version 5.5.6 starting
,E/dhcpcd  ( 7647): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7650): MountEmulatedStorage()
E/Zygote  ( 7650): v2
I/libpersona( 7650): KNOX_SDCARD checking this for 10088
I/libpersona( 7650): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7650 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  873): Killing 6059:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7650): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/dhcpcd  ( 7647): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7647): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7647): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7647): bssid match
,I/dhcpcd  ( 7647): wlan0: rebinding lease of 192.168.1.135
I/SELinux ( 7650): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7650): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  873): failed to open /acct/uid_10042/pid_6059/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7650): TimaSignature is unavailable
,D/ActivityThread( 7650): Added TimaKeyStore provider
,D/ResourcesManager( 7650): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  873): Killing 5681:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/Headlines( 5529): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5529): getCountryCode(): countryCode = DE
,D/Headlines( 5529): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5529): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5529): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5529): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5529): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5529): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5529): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7670): MountEmulatedStorage()
I/libpersona( 7670): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7670): v2
I/libpersona( 7670): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7670 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/CountryDetector(  873): No listener is left
,E/SELinux ( 7670): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  873): failed to open /acct/uid_10050/pid_5681/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7670): TimaSignature is unavailable
,D/ActivityThread( 7670): Added TimaKeyStore provider
,D/ResourcesManager( 7670): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,V/AlarmManager(  873): waitForAlarm result :4
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,W/ContextImpl( 7670): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7670): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7670): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7670): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7670): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7670): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7670): Loading: webviewchromium
,I/LibraryLoader( 7670): Time to load native libraries: 4 ms (timestamps 2792-2796)
,I/LibraryLoader( 7670): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7670): Binding Chromium to main looper Looper (main, tid 1) {13ac47ff}
,I/LibraryLoader( 7670): Expected native library version number "",actual native library version number ""
,I/chromium( 7670): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7670): Initializing chromium process, renderers=0
,W/art     ( 7670): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7670): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7670): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7670): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7670): Requires BLUETOOTH permission
,I/Adreno-EGL( 7670): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7670): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7670): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7670): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7670): Remote Branch: 
I/Adreno-EGL( 7670): Local Patches: 
I/Adreno-EGL( 7670): Reconstruct Branch: 
,I/NSApplication( 7670): Starting up...
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7734): MountEmulatedStorage()
I/libpersona( 7734): KNOX_SDCARD checking this for 10138
E/Zygote  ( 7734): v2
I/libpersona( 7734): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7734 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  873): Killing 6832:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7734): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  873): failed to open /acct/uid_10051/pid_6832/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7734): TimaSignature is unavailable
,D/ActivityThread( 7734): Added TimaKeyStore provider
,D/ResourcesManager( 7734): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7734): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7734): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7734): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7734): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7734): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7749): MountEmulatedStorage()
,E/Zygote  ( 7749): v2
I/libpersona( 7749): KNOX_SDCARD checking this for 10163
I/libpersona( 7749): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7749 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  873): Killing 6850:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7749): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7749): TimaSignature is unavailable
,D/ActivityThread( 7749): Added TimaKeyStore provider
,D/ResourcesManager( 7749): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7749): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7749): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7749): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7749): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  873): failed to open /acct/uid_10058/pid_6850/cgroup.procs: No such file or directory
,D/RCPManagerService(  873): exchangeData() failure , invalid userId
,D/RCPManagerService(  873): exchangeData() failure , invalid userId
,D/RCPManagerService(  873): exchangeData() failure , invalid userId
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  873): exchangeData() failure , invalid userId
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/Zygote  ( 7772): MountEmulatedStorage()
,E/Zygote  ( 7772): v2
I/libpersona( 7772): KNOX_SDCARD checking this for 10078
I/libpersona( 7772): KNOX_SDCARD not a persona
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/ActivityManager(  873): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7772 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,I/art     (  310): Explicit concurrent mark sweep GC freed 8739(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 11.976ms
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.816ms
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.606ms
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,I/SELinux ( 7772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7772): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/RCPManagerService(  873): exchangeData() failure , invalid userId
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/RCPManagerService(  873): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7772): TimaSignature is unavailable
,D/ActivityThread( 7772): Added TimaKeyStore provider
,I/ActivityManager(  873): Killing 6232:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7453): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7453): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7453): StateMachine : Current State = 1
,D/SecurityLogAgent( 7453): StateMachine : Changed Current State = 1
,I/ActivityManager(  873): Killing 6874:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7749): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/com.peel.receiver.ConnectivityActionReceiver( 1749): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1749): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): last run: 1450100212786 -- System.currentTimeMillis()-last_run: 85816
D/com.peel.receiver.ConnectivityActionReceiver( 1749): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): ... skip last_72_check
,I/dhcpcd  ( 7647): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_6232/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10098/pid_6874/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7647): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  873): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  873): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  873): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/art     (  873): Explicit concurrent mark sweep GC freed 60384(3MB) AllocSpace objects, 9(1554KB) LOS objects, 29% free, 37MB/53MB, paused 2.655ms total 111.938ms
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7772): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,I/ActivityManager(  873): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7793 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7793): MountEmulatedStorage()
E/Zygote  ( 7793): v2
I/libpersona( 7793): KNOX_SDCARD checking this for 10178
I/libpersona( 7793): KNOX_SDCARD not a persona
,I/SELinux ( 7793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7793): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/ActivityManager(  873): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 7793): TimaSignature is unavailable
D/ActivityThread( 7793): Added TimaKeyStore provider
,D/BadgeProvider( 7772): onCreate
,D/BadgeProvider( 7772): DatabaseHelper
,D/ResourcesManager( 7793): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7772): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1483): reloadBadges entered.
D/BadgeProvider( 7772): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7772): sendNotify, [notify] : null
D/BadgeProvider( 7772): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7772): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7772): update, [UpdateCount] : 1
,I/ActivityManager(  873): Killing 6937:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,I/iu.Environment( 2482): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2482): num queued entries: 0
,I/iu.UploadsManager( 2482): num updated entries: 0
,I/iu.SyncManager( 2482): NEXT; no task
,D/ChimeraCfgMgr( 2482): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/WifiStateMachine(  873): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  873): InactiveState{ what=143375 }
D/WifiP2pService(  873): P2pEnabledState{ what=143375 }
,E/SMD     (  280): DCD ON
,I/Hs20UtilService( 1300): Starting #8
,E/WifiStateMachine(  873): WifiStateMachine DHCP successful
,E/WifiStateMachine(  873): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/Watchdog(  873): !@Sync 3
D/ConnectivityService(  873): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
I/Hs20UtilService( 1300): Message received 5007
E/WifiStateMachine(  873): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/WifiStateMachine(  873): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiStateMachine(  873): Not connected state, yet.
E/WifiStateMachine(  873): VerifyingLinkState enter
,I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
D/WifiStateMachine(  873): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  873): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  873): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  873): callSECApiInt - ID [210]
E/WifiStateMachine(  873): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  873): updateNetworkInfo()
,D/ConnectivityService(  873): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  873): Adding iface wlan0 to network 503
,I/CLocInfoService(  873): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  873): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger(  873): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  873): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  873): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  873): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,W/libprocessgroup(  873): failed to open /acct/uid_10033/pid_6937/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  873): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  873): Now, connected state.
E/WifiStateMachine(  873): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  873): evaluateTrafficStatsPolling
,D/ConnectivityService(  873): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/CLocInfoService(  873): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  873): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine(  873): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  873): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  873): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  873): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  873): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  275): QcRouteController
,D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  873): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  873): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  873): mBoosterFLAG : 0
I/WifiTrafficPoller(  873): current booster mode : FullMode
,I/Hs20UtilService( 1300): Starting #9
,E/WifiStateMachine(  873): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/WifiNative-HAL(  873): callSECApiVoid - ID [212]
,I/CLocInfoService(  873): External Intent Received android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1167): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
V/        (  275): QcRouteController
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
I/Hs20UtilService( 1300): Message received 5007
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/WifiStateMachine(  873): REQUEST_POWER_SAVE_ON
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,V/        (  275): QcRouteController
,I/Hs20UtilService( 1300): Starting #10
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1300): Message received 5007
,V/NearbySettings( 1300): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1300): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1300): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1300): MountReceiver.mPrefHandler - 7002
,V/        (  275): QcRouteController
,I/Hs20UtilService( 1300): Starting #11
,I/Hs20UtilService( 1300): Message received 5007
,D/NearbySettings( 1300): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1300): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  873): callSECApi what=220
D/WifiStateMachine(  873): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/        (  275): QcRouteController
,D/PowerManagerService(  873): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=873
,D/DisplayPowerController(  873): getFinalBrightness : 30 -> 30
D/PowerManagerService(  873): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  873): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  873): calling update connectivity
D/ConnectivityService(  873): ignoring duplicate network state non-change
E/ConnectivityService(  873): updateNetworkInfo()
D/ConnectivityService(  873): ignoring duplicate network state non-change
E/ConnectivityService(  873): updateNetworkInfo()
D/ConnectivityService(  873): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  873): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  873): calling update connectivity
D/ConnectivityService(  873): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  873): Validated
D/ConnectivityService(  873):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  873):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  873): currentScore = 0, newScore = 60
D/ConnectivityService(  873):    accepting network in place of null
D/ConnectivityService(  873): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1461): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  873): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  873): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  873): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/lights  (  873): lcd : 23 +
,D/ConnectivityService(  873): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  873): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  873): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SmartBondingService(  873): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
,D/EntConnectivity(  873): Not allowed due to - mEnabled false
D/ConnectivityService(  873): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  873): calling update connectivity
,D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  873): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  873):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524290
D/ConnectivityService(  873):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,V/NetworkStats(  873): updateIfacesLocked()
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
V/NetworkStats(  873): performPollLocked(flags=0x1)
D/SmartBondingService(  873): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  873): UpdateStatsForKnox
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
V/NetworkStats(  873): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/ConnectivityService(  873): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  873): calling update connectivity
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  873): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/lights  (  873): lcd : 23 -
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524290
,V/NetworkStats(  873): performPollLocked() took 5ms
,D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/DisplayPowerController(  873): getFinalBrightness : 30 -> 30
D/lights  (  873): lcd : 30 +
,D/lights  (  873): lcd : 30 -
,D/DisplayPowerController(  873): getFinalBrightness : 30 -> 30
,D/NtpTrustedTime(  873): currentTimeMillis() cache hit
D/NtpTrustedTime(  873): currentTimeMillis() cache hit
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBar.NetworkController( 1167): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1167): updateDataNetType()
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1167): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1167): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1167): updateDataNetType()
D/StatusBar.NetworkController( 1167): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1167): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  873): MasterInitialState.processMessage what=3
,D/SmartBondingService(  873): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  873): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  873): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  873): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  873): getSBEnabled() enabled =false
,D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
,I/CLocInfoService(  873): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  873): CLocinfo wifi true 
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  873): getNetworkEnabled : wifi : true mobile : true
D/accuweather( 2140): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2208): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2208): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3819): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3819): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/SystemBroadcastReceiver( 7155): [#DCM#] [DCM_Performance] onReceive completed in time  260 microsec. 
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/NetworkMonitor( 5389): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7155): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7155): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7155): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/DatabaseRebuilderTask( 7155): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,I/PCWCLIENTTRACE_PushUtil( 6773): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6773): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6773): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6773): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/FrameworkService( 7155): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7155): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7155): [#DCM#] getSuccessState = true
I/FrameworkService( 7155): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7155): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,I/DIAGMON_AGENT( 7536): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7536): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SystemUtils( 7155): [#DCM#] LM: false,AM:689008640
,I/DCMThreadPoolExecutor( 7155): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7155): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1a24dc79 is submitted
I/FrameworkService( 7155): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 24060 mirosec. 
,I/DatabaseRebuilderTask( 7155): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7155): [#DCM#] resyncLocation   
,I/DatabaseRebuilderTask( 7155): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7155): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7155): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7155): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7155): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7155): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7155): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7155): [#DCM#] afterExecute FutureTask
,I/DCMController( 7155): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1a24dc79
,I/FOTA_Client( 7554): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7554): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7554): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7554): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7554): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7574): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7574): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450100299789
,I/KLMS-2.4.503: ( 7574): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7574): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7574): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7574): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7574): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7589): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5152): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6811): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6811): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6811): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6811): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6811): [OR] == isSIMCardReady false ==
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6811): [SCU] == networkStateCheck == true
,I/SA      ( 6811): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6811): isChinaCountryCode : false
I/SA      ( 6811): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 6811): [OR] == networkStateCheck true ==
,I/SA      ( 6811): [OR] GetMyCountryZoneTask
,I/SA      ( 6811): [OR] onReceive END
,I/SA      ( 6811): [SRS] prepareGetMyCountryZone
,I/SA      ( 6811): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6811): [SSP] query invoked
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6811): [TPMU] GetMccFromDB : null
I/SA      ( 6811): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6811): [TPM] isNoProxy(default) : true
,D/accuweather( 7611): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7611): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/File    ( 6811): fail readDirectory() errno=2
,I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7629): premStatus:2
,I/KnoxUsageLogPro( 7629): isEulaShown : false
I/KnoxUsageLogPro( 7629): KnoxUsageReceiver onReceive : not Processible, just return
,D/Headlines( 5529): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5529): getCountryCode(): countryCode = DE
,D/Headlines( 5529): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5529): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5529): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5529): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5529): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5529): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5529): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7734): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7734): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7734): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/RCPManagerService(  873): exchangeData() failure , invalid userId
,D/RCPManagerService(  873): exchangeData() failure , invalid userId
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7453): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7453): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7453): StateMachine : Current State = 1
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7453): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1749): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): last run: 1450100212786 -- System.currentTimeMillis()-last_run: 87196
,D/com.peel.receiver.ConnectivityActionReceiver( 1749): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1749): ... skip last_72_check
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2482): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2482): num queued entries: 0
,I/iu.UploadsManager( 2482): num updated entries: 0
,I/iu.SyncManager( 2482): NEXT; no task
,D/ChimeraCfgMgr( 2482): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2482): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7133): notifyNetworkActivated
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7133): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  873): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 29434(1796KB) AllocSpace objects, 14(1134KB) LOS objects, 39% free, 17MB/29MB, paused 435us total 35.337ms
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2482): [AccountUtils] Account not ready
W/Kids    ( 2482): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2482): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2482): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2482): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2482): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2482): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2482): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2482): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2482): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/GCM     ( 1674): Connected
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1674): Message class com.google.f.a.a.p
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7133): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7133): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7133): exit::IDLE
D/InitializeManagerStateMachine( 7133): entry::NETWORK_CHECK
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7133): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7133): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7133): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7133): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7133): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7133): entry::SUCCESS
D/hcjo    ( 7133): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7133): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7133): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7133): exit::SUCCESS
D/InitializeManagerStateMachine( 7133): entry::IDLE
,I/SA      ( 6811): [RC New] Execute method=[GET] start
,I/SA      ( 6811): [RC New] Security=[true]
,I/System.out( 6811): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6811): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6811): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7387): BLE supported!!
I/jxcore-log( 7387): 
,I/SA      ( 6811): [RC New] [v2liruge] api execute + 925
I/SA      ( 6811): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6811): AsyncTask #1 calls detatch()
,I/SA      ( 6811): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6811): [OCP] update openData : PL
,I/SA      ( 6811): [TPMU] getNetworkMcc : 
,I/SA      ( 6811): [SCU] saveMccToPreferece Start
,I/SA      ( 6811): [SCU] RegionMCC : 260
I/SA      ( 6811): [SSP] query invoked
,I/SA      ( 6811): [TPMU] GetMccFromDB : null
,I/SA      ( 6811): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6811): [SCU] saveMccToPreferece End
I/SA      ( 6811): [RC New] executeRequest [v2liruge] end. 1007
,I/SA      ( 6811): [RC New] Execute end
I/SA      ( 6811): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6811): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 7647): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7647): wlan0: sendmsg: Cannot assign requested address
,D/PowerManagerService(  873): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  873): [PWL] On : 76582 (30001 ms ago)
,I/PowerManagerService(  873): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,I/PowerManagerService(  873): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=873, ws=WorkSource{10059}) (elapsedTime=2820)
,E/SMD     (  280): DCD ON
,I/WifiStateMachine(  873): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  873): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PowerManagerService(  873): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 873) eventTime = 107257
,D/PowerManagerService(  873): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  873): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=873 (0x0)
,D/PowerManagerService(  873): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=873, ws=WorkSource{10059}) (elapsedTime=3490)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/SSRM:m  (  873): SIOP:: AP = 400, PST = 424, CUR = 300
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,E/WifiStateMachine(  873): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  873): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  873): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  873): identical MTU - not setting
E/WifiStateMachine(  873): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  873): updateSourceRoutes : add source routing for type : 1
V/        (  275): QcRouteController
D/ConnectivityService(  873): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
D/SmartBondingService(  873): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  873): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
D/SmartBondingService(  873): getSBEnabled() enabled =false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/        (  275): QcRouteController
,W/NetworkManagementService(  873): route cmd failed: 
W/NetworkManagementService(  873): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '71 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 71 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  873): '
W/NetworkManagementService(  873): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  873): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  873): ,	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  873): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  873): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  873): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  873): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  873): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  873): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  873): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  873): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  873): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  873): calling update connectivity
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524295
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1167): value : false
D/ConnectivityService(  873): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  873): calling update connectivity
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
D/ConnectivityManager.CallbackHandler( 1167): CM callback handler got msg 524295
D/ConnectivityService(  873):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  873): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/GAV4    ( 7670): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6773): mConnectivityHandler : connected,
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6773): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6773): ================================================
,I/CSTORAGE( 6773):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6773): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6773): [GetString-S]
,E/art     ( 6773): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6773): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6773): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6773): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6773): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6773): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6773): [ensureRegistration] - No Samsung account
,E/SMD     (  280): DCD ON
,I/dhcpcd  ( 7647): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,I/dhcpcd  ( 7647): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7647): wlan0: no IPv6 Routers available
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7133): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7133): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7133): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7133): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7133): RestApi Request Add : 2307
,E/File    ( 7133): fail readDirectory() errno=2
,D/FactoryTest( 6494): Not factory mode
,D/FactoryTest( 6494): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6494): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6494): still no open session command from host, so toast
,W/ContextImpl( 6494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6494): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6494): Timeline: Activity_launch_request id:com.android.settings time:115533
,E/PersonaManagerService(  873): inState():  stateMachine is null !!
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  873): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  873): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  873): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 6494): started activity for popup
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ResourcesManager( 6494): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6494): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6494): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6494): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/ActivityManager(  873): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  873): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/SMD     (  280): DCD ON
I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,W/InputMethodManagerService(  873): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3203a4e0 attribute=null, token = android.os.BinderProxy@2995cc90
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
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6494): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6494): dev.kiessupport is : TRUE
,D/Activity( 6494): performCreate Call secproduct feature valuefalse
D/Activity( 6494): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ActivityManager(  873): post active user change for 0
D/KnoxTimeoutHandler(  873): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  873): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/System.out( 7133): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 7133): (HTTPLog)-Static: isShipBuild true
,I/System.out( 7133): (HTTPLog)-Thread-1187-1071306628: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/Timeline( 7387): Timeline: Activity_idle id: android.os.BinderProxy@29e12810 time:115760
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,V/BitmapFactory( 1167): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/qtaguid ( 7133): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7133, getuid(): 10040
,I/qtaguid ( 7133): Untagging socket 26
,D/hcjo    ( 7133): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 7133): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 7133): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7133): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7133): entry::REQ_UPDATE_CHECK
,I/Volley  ( 7133): RestApi Request Add : 2315
,I/qtaguid ( 7133): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7133, getuid(): 10040
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7133): Untagging socket -1
I/qtaguid ( 7133): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 7133): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 7133): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 7133): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 7133): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 7133): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7133): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7133): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 7133): exit::FINISH
D/PreloadUpdateManagerStateMachine( 7133): entry::IDLE
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,D/SSRM:m  (  873): SIOP:: AP = 360, PST = 413, CUR = 300
,V/AlarmManager(  873): waitForAlarm result :4
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 3.
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,D/CustomFrequencyManagerService(  873): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  873): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  873): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/SMD     (  280): DCD ON
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/CustomFrequencyManagerService(  873): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 873  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 340, PST = 399, CUR = 300
D/X       (  873): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1226):  LEVEL : -1
,I/SystemBroadcastReceiver( 7155): [#DCM#] [DCM_Performance] onReceive completed in time  423 microsec. 
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/SystemBroadcastReceiver( 7155): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7155): [#DCM#] onReceive action = EVENT_SIOP
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7953): MountEmulatedStorage()
E/Zygote  ( 7953): v2
I/libpersona( 7953): KNOX_SDCARD checking this for 10054
I/libpersona( 7953): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7953 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 7953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7953): TimaSignature is unavailable
,D/ActivityThread( 7953): Added TimaKeyStore provider
,D/ResourcesManager( 7953): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7953): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7953): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7953): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7953): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/TranscodeReceiver( 7953): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 7953): core_num = 4
,W/linker  ( 7953): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 7953): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 7953): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 7953): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 7953):  SIOP_LEVEL: -1
,I/ActivityManager(  873): Killing 6907:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,W/libprocessgroup(  873): failed to open /acct/uid_10099/pid_6907/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,E/SMD     (  280): DCD ON
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/PowerManagerService(  873): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  873): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  873): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  873): lcd : 19 +
,D/lights  (  873): lcd : 19 -
,D/DisplayPowerController(  873): getFinalBrightness : 15 -> 15
D/lights  (  873): lcd : 15 +
,D/lights  (  873): lcd : 15 -
,D/DisplayPowerController(  873): getFinalBrightness : 15 -> 15
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!,
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,E/Watchdog(  873): !@Sync 4
,E/SMD     (  280): DCD ON
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  873): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  873): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,E/SMD     (  280): DCD ON
,D/PowerManagerService(  873): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  873): Nap time (uid 1000)...
,I/PowerManagerService(  873): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  873): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  873): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  873): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  873): setDeviceInteractive: 0
,D/PowerManagerService(  873): handleSandman : startDream()
,D/InputManager-JNI(  873): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  873): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  873): Sleeping (uid 1000)...
D/PowerManagerService(  873): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  873): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  873): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  873): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  873): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  873): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  873): 	.unregisterCallback : 1, client=
,D/SContextService(  873): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3542044, Service = Auto Rotation, used = 1
,W/CAE     (  873): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  873): stop(ContextProvider.java:149)
,V/CAE     (  873): clear(AutoRotationRunner.java:182)
,V/CAE     (  873): disable(AutoRotationRunner.java:171)
,I/CAE     (  873): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  873): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  296): sendContextData: -78, 7, 0, 0
,D/CAE     (  873): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  873): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  873): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  873): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  873): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  873): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  873): removeSContextService() : service = Auto Rotation
D/SContextService(  873): ===== SContext Service List =====
D/SContextManager(  873):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@28884d5a, service=Auto Rotation
,D/KeyguardViewMediator( 1167): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1167): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1167): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1167): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/KeyguardViewMediator( 1167): timeout : 5000
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SQLiteSecureOpenHelper( 3539): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3539): getDatabaseLocked(b,b,pwd)...
,D/DisplayPowerController(  873): ColorFade: onAnimationStart
D/DisplayPowerController(  873): getFinalBrightness : 30 -> 0
,D/lights  (  873): lcd : 10 +
,D/lights  (  873): lcd : 10 -
,D/lights  (  873): lcd : 2 +
,D/KeyguardViewMediator( 1167): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1167): handleNotifyScreenOff
,D/lights  (  873): lcd : 2 -
,D/lights  (  873): lcd : 0 +
,D/DisplayPowerController(  873): getFinalBrightness : 30 -> 0
,D/SSRM:m  (  873): SIOP:: AP = 330, PST = 383, CUR = 300
,D/LightsService(  873): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 873) 
,D/LightsService(  873): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  873): [SvcLED]  onSensorChanged::light value = 15
,D/SensorManager(  873): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  873): turn on LED for fully charged
,D/SensorManager(  873): unregisterListener ::   
,D/lights  (  873): lcd : 0 -
,D/lights  (  873): led_pattern : 5 +
,I/CAE     (  873): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  873): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  873): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  873): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  296): sendContextData: -76, 13, -46, 0
,D/lights  (  873): led_pattern : 5 -
D/LightsService(  873): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  873): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 13, 38, 52,
D/SensorHubManager(  873): SendSensorHubData: send data = -63, 14, 13, 38, 52
,D/Sensorhubs(  296): sendContextData: -63, 14, 13, 38, 52
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  873):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  873): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  873): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  873): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  873): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,D/NotificationService(  873): ACTION_SCREEN_OFF
E/native  (  873): do suspend true
,D/LightsService(  873): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 873) 
D/LightsService(  873): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  873): [SvcLED]  onSensorChanged::light value = 15
,D/SensorManager(  873): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  873): unregisterListener ::   
D/LightsService(  873): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  289): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  873): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  873): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  873): Bridge Server is not available
,D/VolumePanel( 1167): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1167): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1167): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1167): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  873): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  873): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1455): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1167):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1167): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1167): dismissHelpPopup 
,D/DisplayPowerState(  873): !@ ColorFade entry
D/DisplayPowerController(  873): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  873): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  873): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  873): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/AutomaticBrightnessController(  873): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  873): Light old sensor_state 8705, new sensor_state : 8193 en : 0
D/accuweather( 2140): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2140): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/SensorManager(  873): unregisterListener ::   
E/Sensors (  873): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  873): unregisterListener ::   
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  873): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  873): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
I/DisplayManagerService(  873): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  873): Display changed displayId=0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/ActivityManager(  873): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  873): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  873): SIOP:: AP = 330, PST = 371, CUR = 300
,I/SystemBroadcastReceiver( 7155): [#DCM#] [DCM_Performance] onReceive completed in time  198 microsec. 
,I/SystemBroadcastReceiver( 7155): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7155): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7155): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  873): [PWL] sb release: PowerManagerService.Broadcasts
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/AlarmManager(  873): waitForAlarm result :4
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  270): 
,I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  873): Excessive delay in setPowerMode(): 272ms
D/PowerManagerService(  873): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  873): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  873): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  873): Got set_interactive hint
,I/PowerManagerService(  873): [PWL] Off : 0s ago
,I/PowerManagerService(  873): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  873): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  873): getFinalBrightness : 0 -> 0
D/PowerManagerService(  873): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  873): [PWL] sb release: PowerManagerService.Display
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardViewMediator( 1167): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1167): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/KeyguardViewMediator( 1167): doKeyguard: not showing because lockscreen is off
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  873): [PWL] Off : 5s ago
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 320, PST = 362, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  873): [PWL] Off : 15s ago
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6633): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at dsf.a(PG:807)
E/HttpOperation( 6633): 	at fhk.a(PG:1126)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 8 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 10 more
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms,
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at ieo.a(PG:43)
E/HttpOperation( 6633): 	at iep.a(PG:93)
E/HttpOperation( 6633): 	at fhn.a(PG:59)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/ExperimentLoader( 6633): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): 	at kfv.a(PG:65)
E/ExperimentLoader( 6633): 	at kff.u(PG:385)
E/ExperimentLoader( 6633): 	at kfb.a(PG:29)
E/ExperimentLoader( 6633): 	at kff.l(PG:132)
E/ExperimentLoader( 6633): 	at ieo.a(PG:43)
E/ExperimentLoader( 6633): 	at iep.a(PG:93)
E/ExperimentLoader( 6633): 	at fhn.a(PG:59)
E/ExperimentLoader( 6633): 	at lex.a(PG:85)
E/ExperimentLoader( 6633): 	at lex.b(PG:132)
E/ExperimentLoader( 6633): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6633): 	at fhk.a(PG:908)
E/ExperimentLoader( 6633): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6633): 	at ihi.a(PG:22)
E/ExperimentLoader( 6633): 	at kft.a(PG:91)
E/ExperimentLoader( 6633): 	at kfv.a(PG:62)
E/ExperimentLoader( 6633): 	... 12 more
E/ExperimentLoader( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6633): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6633): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6633): 	at ihi.a(PG:19)
E/ExperimentLoader( 6633): 	... 14 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getaccountstatus] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at ixd.a(PG:248)
E/HttpOperation( 6633): 	at ixd.b(PG:206)
E/HttpOperation( 6633): 	at ixd.a(PG:175)
E/HttpOperation( 6633): 	at fig.a(PG:78)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/EsSyncAdapterService( 6633): Sync failure
E/EsSyncAdapterService( 6633): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6633): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6633): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6633): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6633): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6633): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6633): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6633): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6633): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6633): 	... 10 more
E/EsSyncAdapterService( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6633): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6633): 	... 12 more
E/EsSyncAdapterService( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6633): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6633): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6633): 	... 14 more
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 155619, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  873): Explicit concurrent mark sweep GC freed 77287(4MB) AllocSpace objects, 26(3MB) LOS objects, 29% free, 37MB/53MB, paused 1.661ms total 130.918ms
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7318): Starting books sync, d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,E/SMD     (  280): DCD ON
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4174794382517353156&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  873): SIOP:: AP = 320, PST = 353, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  873): waitForAlarm result :4
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7318): null auth token
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4174794382517353156&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4174794382517353156&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/BooksSync( 7318): Soft error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4174794382517353156&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7318): Sync error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4174794382517353156&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7318): Finished books sync
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 156572, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  873): mCursor = null
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  873): !@Sync 5
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 310, PST = 344, CUR = 300
,I/PowerManagerService(  873): [PWL] Off : 30s ago
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 310, PST = 338, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  873): stay LED for fully charged
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1674): Vacuum at: now=1450100374694 tag=VacuumService
,I/GoogleURLConnFactory( 1674): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1674): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1674): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1674): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1674): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/System.out( 1674): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1674): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1674): (HTTPLog)-Thread-199-848167653: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1674): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1674): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6663): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674): No account for auth token provided
,I/qtaguid ( 1674): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,W/Uploader( 1674):  no longer exists, so no auth token.
,I/qtaguid ( 1674): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1674, getuid(): 10012
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  873): [PWL] Off : 50s ago
,D/SSRM:m  (  873): SIOP:: AP = 310, PST = 333, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  873): !@Sync 6
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 323, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0,
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000,
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 317, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  873): [PWL] Off : 75s ago
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7318): Starting books sync, d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7318): null auth token
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,E/HttpOperation( 6633): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at dsf.a(PG:807)
E/HttpOperation( 6633): 	at fhk.a(PG:1126)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 8 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 10 more
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8787165436887463857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 61939(3MB) AllocSpace objects, 68(4MB) LOS objects, 40% free, 18MB/30MB, paused 906us total 89.774ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6633): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at ieo.a(PG:43)
E/HttpOperation( 6633): 	at iep.a(PG:93)
E/HttpOperation( 6633): 	at fhn.a(PG:59)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/ExperimentLoader( 6633): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): 	at kfv.a(PG:65)
E/ExperimentLoader( 6633): 	at kff.u(PG:385)
E/ExperimentLoader( 6633): 	at kfb.a(PG:29)
E/ExperimentLoader( 6633): 	at kff.l(PG:132)
E/ExperimentLoader( 6633): 	at ieo.a(PG:43)
E/ExperimentLoader( 6633): 	at iep.a(PG:93)
E/ExperimentLoader( 6633): 	at fhn.a(PG:59)
E/ExperimentLoader( 6633): 	at lex.a(PG:85)
E/ExperimentLoader( 6633): 	at lex.b(PG:132)
E/ExperimentLoader( 6633): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6633): 	at fhk.a(PG:908)
E/ExperimentLoader( 6633): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6633): 	at ihi.a(PG:22)
E/ExperimentLoader( 6633): 	at kft.a(PG:91)
E/ExperimentLoader( 6633): 	at kfv.a(PG:62)
E/ExperimentLoader( 6633): 	... 12 more
E/ExperimentLoader( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6633): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6633): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6633): 	at ihi.a(PG:19)
E/ExperimentLoader( 6633): 	... 14 more
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getaccountstatus] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at ixd.a(PG:248)
E/HttpOperation( 6633): 	at ixd.b(PG:206)
E/HttpOperation( 6633): 	at ixd.a(PG:175)
E/HttpOperation( 6633): 	at fig.a(PG:78)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/EsSyncAdapterService( 6633): Sync failure
E/EsSyncAdapterService( 6633): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6633): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6633): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6633): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6633): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6633): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6633): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6633): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6633): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6633): 	... 10 more
E/EsSyncAdapterService( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6633): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6633): 	... 12 more
E/EsSyncAdapterService( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6633): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6633): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6633): 	... 14 more
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 187433, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  873): Explicit concurrent mark sweep GC freed 46017(2MB) AllocSpace objects, 30(1000KB) LOS objects, 29% free, 37MB/53MB, paused 1.461ms total 105.483ms
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 313, CUR = 300
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8787165436887463857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8787165436887463857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7318): Soft error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8787165436887463857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7318): Sync error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8787165436887463857&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7318): Finished books sync
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 193231, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  873): mCursor = null
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/Watchdog(  873): !@Sync 7
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 310, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 307, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 105s ago
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 305, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  873): !@Sync 8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 140s ago
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 300, CUR = 300
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6633): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at dsf.a(PG:807)
E/HttpOperation( 6633): 	at fhk.a(PG:1126)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 8 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 10 more
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at ieo.a(PG:43)
E/HttpOperation( 6633): 	at iep.a(PG:93)
E/HttpOperation( 6633): 	at fhn.a(PG:59)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/ExperimentLoader( 6633): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): 	at kfv.a(PG:65)
E/ExperimentLoader( 6633): 	at kff.u(PG:385)
E/ExperimentLoader( 6633): 	at kfb.a(PG:29)
E/ExperimentLoader( 6633): 	at kff.l(PG:132)
E/ExperimentLoader( 6633): 	at ieo.a(PG:43)
E/ExperimentLoader( 6633): 	at iep.a(PG:93)
E/ExperimentLoader( 6633): 	at fhn.a(PG:59)
E/ExperimentLoader( 6633): 	at lex.a(PG:85)
E/ExperimentLoader( 6633): 	at lex.b(PG:132)
E/ExperimentLoader( 6633): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6633): 	at fhk.a(PG:908)
E/ExperimentLoader( 6633): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6633): 	at ihi.a(PG:22)
E/ExperimentLoader( 6633): 	at kft.a(PG:91)
E/ExperimentLoader( 6633): 	at kfv.a(PG:62)
E/ExperimentLoader( 6633): 	... 12 more
E/ExperimentLoader( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6633): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6633): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6633): 	at ihi.a(PG:19)
E/ExperimentLoader( 6633): 	... 14 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getaccountstatus] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at ixd.a(PG:248)
E/HttpOperation( 6633): 	at ixd.b(PG:206)
E/HttpOperation( 6633): 	at ixd.a(PG:175)
E/HttpOperation( 6633): 	at fig.a(PG:78)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/EsSyncAdapterService( 6633): Sync failure
E/EsSyncAdapterService( 6633): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6633): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6633): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6633): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6633): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6633): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6633): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6633): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6633): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6633): 	... 10 more
E/EsSyncAdapterService( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6633): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6633): 	... 12 more
E/EsSyncAdapterService( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6633): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6633): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6633): 	... 14 more
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 278436, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 9
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 298, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 297, CUR = 300
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 296, CUR = 300
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7318): Starting books sync, d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7606677003738835169&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7606677003738835169&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/TimaService(  873): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  873): TimaServiceHandler.handleMessage what =1
,D/TimaService(  873): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  873): initializing...
,I/TLC_TIMA_PKM_initialize(  873): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  873): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  873): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  873): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  873): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  873): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  873): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  873): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  873): App is not loaded in QSEE
,D/QSEECOMAPI: (  873): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  873): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  873): Trustlet response is completed
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7606677003738835169&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/BooksSync( 7318): Soft error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7606677003738835169&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7318): Sync error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7606677003738835169&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7318): Finished books sync
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284620, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  873): mCursor = null
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  873): !@Sync 10
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 180s ago
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/SSRM:m  (  873): SIOP:: AP = 300, PST = 296, CUR = 300
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,E/Zygote  ( 8228): MountEmulatedStorage()
,D/BatteryService(  873): stay LED for fully charged
E/Zygote  ( 8228): v2
,I/libpersona( 8228): KNOX_SDCARD checking this for 10081
I/libpersona( 8228): KNOX_SDCARD not a persona
,I/ActivityManager(  873): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8228 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,I/SELinux ( 8228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8228): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 8228): TimaSignature is unavailable
,D/ActivityThread( 8228): Added TimaKeyStore provider
,D/ResourcesManager( 8228): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  873): Killing 6970:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,W/libprocessgroup(  873): failed to open /acct/uid_10003/pid_6970/cgroup.procs: No such file or directory
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  873): waitForAlarm result :4
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 294, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  873): !@Sync 11
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6663): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6663): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6663): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6663): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6663): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6663): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6663): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/art     (  873): Explicit concurrent mark sweep GC freed 46791(2MB) AllocSpace objects, 54(1449KB) LOS objects, 29% free, 37MB/53MB, paused 1.813ms total 161.160ms
,W/System  ( 6663): Ignoring header User-Agent because its value was null.
,I/System.out( 6663): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6663): (HTTPLog)-Static: isShipBuild true
I/System.out( 6663): (HTTPLog)-Thread-1093-459317453: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/PowerManagerService(  873): [PWL] Off : 225s ago
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  873): !@Sync 12
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  873): waitForAlarm result :8
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6633): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at dsf.a(PG:807)
E/HttpOperation( 6633): 	at fhk.a(PG:1126)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 8 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 10 more
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at ieo.a(PG:43)
E/HttpOperation( 6633): 	at iep.a(PG:93)
E/HttpOperation( 6633): 	at fhn.a(PG:59)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/ExperimentLoader( 6633): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): 	at kfv.a(PG:65)
E/ExperimentLoader( 6633): 	at kff.u(PG:385)
E/ExperimentLoader( 6633): 	at kfb.a(PG:29)
E/ExperimentLoader( 6633): 	at kff.l(PG:132)
E/ExperimentLoader( 6633): 	at ieo.a(PG:43)
E/ExperimentLoader( 6633): 	at iep.a(PG:93)
E/ExperimentLoader( 6633): 	at fhn.a(PG:59)
E/ExperimentLoader( 6633): 	at lex.a(PG:85)
E/ExperimentLoader( 6633): 	at lex.b(PG:132)
E/ExperimentLoader( 6633): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6633): 	at fhk.a(PG:908)
E/ExperimentLoader( 6633): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6633): 	at ihi.a(PG:22)
E/ExperimentLoader( 6633): 	at kft.a(PG:91)
E/ExperimentLoader( 6633): 	at kfv.a(PG:62)
E/ExperimentLoader( 6633): 	... 12 more
E/ExperimentLoader( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6633): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6633): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6633): 	at ihi.a(PG:19)
E/ExperimentLoader( 6633): 	... 14 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getaccountstatus] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at ixd.a(PG:248)
E/HttpOperation( 6633): 	at ixd.b(PG:206)
E/HttpOperation( 6633): 	at ixd.a(PG:175)
E/HttpOperation( 6633): 	at fig.a(PG:78)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/EsSyncAdapterService( 6633): Sync failure
E/EsSyncAdapterService( 6633): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6633): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6633): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6633): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6633): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6633): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6633): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6633): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6633): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6633): 	... 10 more
E/EsSyncAdapterService( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6633): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6633): 	... 12 more
E/EsSyncAdapterService( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6633): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6633): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6633): 	... 14 more
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 401536, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2860): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog(  873): !@Sync 13
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  873): [PWL] Off : 275s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 14
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7387): Connected to the server!
I/jxcore-log( 7387): 
,I/chromium( 7387): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7318): Starting books sync, d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 40624(2MB) AllocSpace objects, 31(2MB) LOS objects, 39% free, 18MB/30MB, paused 1.635ms total 71.119ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=434826011630637574&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  873): !@Sync 15
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/SMD     (  280): DCD ON
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
,W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=434826011630637574&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=434826011630637574&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7318): Soft error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=434826011630637574&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7318): Sync error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=434826011630637574&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7318): Finished books sync
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 440583, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2860): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2860): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  873): mCursor = null
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/PowerManagerService(  873): [PWL] Off : 330s ago
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/bootchecker(  316): bootchecker wake up!!
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 16
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  873): waitForAlarm result :8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 17
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/PowerManagerService(  873): [PWL] Off : 390s ago
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  280): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  873): !@Sync 18
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/Atfwd_Daemon(  320): Stop the daemon....
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 19
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 455s ago
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/TimaService(  873): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  873): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  873): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  873): !@Sync 20
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/ActivityManager(  873): Killing 6985:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,W/libprocessgroup(  873): failed to open /acct/uid_10020/pid_6985/cgroup.procs: No such file or directory
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 21
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6633): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at dsf.a(PG:807)
E/HttpOperation( 6633): 	at fhk.a(PG:1126)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 8 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 10 more
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6633): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at ieo.a(PG:43)
E/HttpOperation( 6633): 	at iep.a(PG:93)
E/HttpOperation( 6633): 	at fhn.a(PG:59)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/ExperimentLoader( 6633): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): 	at kfv.a(PG:65)
E/ExperimentLoader( 6633): 	at kff.u(PG:385)
E/ExperimentLoader( 6633): 	at kfb.a(PG:29)
E/ExperimentLoader( 6633): 	at kff.l(PG:132)
E/ExperimentLoader( 6633): 	at ieo.a(PG:43)
E/ExperimentLoader( 6633): 	at iep.a(PG:93)
E/ExperimentLoader( 6633): 	at fhn.a(PG:59)
E/ExperimentLoader( 6633): 	at lex.a(PG:85)
E/ExperimentLoader( 6633): 	at lex.b(PG:132)
E/ExperimentLoader( 6633): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6633): 	at fhk.a(PG:908)
E/ExperimentLoader( 6633): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6633): 	at ihi.a(PG:22)
E/ExperimentLoader( 6633): 	at kft.a(PG:91)
E/ExperimentLoader( 6633): 	at kfv.a(PG:62)
E/ExperimentLoader( 6633): 	... 12 more
E/ExperimentLoader( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6633): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6633): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6633): 	at ihi.a(PG:19)
E/ExperimentLoader( 6633): 	... 14 more
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6633): [getaccountstatus] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at ixd.a(PG:248)
E/HttpOperation( 6633): 	at ixd.b(PG:206)
E/HttpOperation( 6633): 	at ixd.a(PG:175)
E/HttpOperation( 6633): 	at fig.a(PG:78)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/EsSyncAdapterService( 6633): Sync failure
E/EsSyncAdapterService( 6633): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6633): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6633): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6633): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6633): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6633): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6633): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6633): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6633): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6633): 	... 10 more
E/EsSyncAdapterService( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6633): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6633): 	... 12 more
E/EsSyncAdapterService( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6633): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6633): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6633): 	... 14 more
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 646521, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  873): [PWL] Off : 525s ago
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  873): stay LED for fully charged
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 22
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 23
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7318): Starting books sync, d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7318): null auth token
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5135805837057656727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5135805837057656727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1167): Explicit concurrent mark sweep GC freed 74814(4MB) AllocSpace objects, 51(4MB) LOS objects, 30% free, 37MB/53MB, paused 3.870ms total 141.184ms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5135805837057656727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7318): Soft error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5135805837057656727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7318): Sync error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5135805837057656727&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7318): Finished books sync
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 721923, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  873): Explicit concurrent mark sweep GC freed 69245(4MB) AllocSpace objects, 127(2MB) LOS objects, 29% free, 37MB/53MB, paused 1.877ms total 140.410ms
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 24
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 600s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON,
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 25
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 26
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 680s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 27
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/Watchdog(  873): !@Sync 28
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 29
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  873): [PWL] Off : 765s ago
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  873): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  873): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  873): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 30
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 31
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 32
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  873): [PWL] Off : 855s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 33
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/LightsService(  873): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/Finsky  ( 6663): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,E/LightSensor(  873): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/SensorManager(  873): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1674): Message class com.google.f.a.a.i
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Finsky  ( 6663): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/EventLogService( 2482): Aggregate from 1450099218436 (log), 1450099218436 (data)
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LightsService(  873): [SvcLED]  onSensorChanged::light value = 8
E/LightSensor(  873): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SensorManager(  873): unregisterListener ::   
D/LightsService(  873): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6663): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6663): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6663): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6663): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6663): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 2222): client connected with version: 7571000
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300,
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/BatteryService(  873): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 34
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1674): Explicit concurrent mark sweep GC freed 37290(2MB) AllocSpace objects, 20(1620KB) LOS objects, 40% free, 18MB/30MB, paused 692us total 42.727ms
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 3.
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 35
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 950s ago
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 36
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  873): waitForAlarm result :4
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6663): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 37
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6663): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6663): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6663): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at dsf.a(PG:807)
E/HttpOperation( 6633): 	at fhk.a(PG:1126)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 8 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 10 more
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SMD     (  280): DCD ON
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6633): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at kff.l(PG:132)
E/HttpOperation( 6633): 	at ieo.a(PG:43)
E/HttpOperation( 6633): 	at iep.a(PG:93)
E/HttpOperation( 6633): 	at fhn.a(PG:59)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,I/PhoneStatusBar( 1167): Icon Only
E/ExperimentLoader( 6633): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6633): 	at kfv.a(PG:65)
E/ExperimentLoader( 6633): 	at kff.u(PG:385)
E/ExperimentLoader( 6633): 	at kfb.a(PG:29)
E/ExperimentLoader( 6633): 	at kff.l(PG:132)
E/ExperimentLoader( 6633): 	at ieo.a(PG:43)
E/ExperimentLoader( 6633): 	at iep.a(PG:93)
E/ExperimentLoader( 6633): 	at fhn.a(PG:59)
E/ExperimentLoader( 6633): 	at lex.a(PG:85)
E/ExperimentLoader( 6633): 	at lex.b(PG:132)
E/ExperimentLoader( 6633): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6633): 	at fhk.a(PG:908)
E/ExperimentLoader( 6633): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6633): 	at ihi.a(PG:22)
E/ExperimentLoader( 6633): 	at kft.a(PG:91)
E/ExperimentLoader( 6633): 	at kfv.a(PG:62)
E/ExperimentLoader( 6633): 	... 12 more
E/ExperimentLoader( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6633): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6633): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6633): 	at ihi.a(PG:19)
E/ExperimentLoader( 6633): 	... 14 more
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6633): [getaccountstatus] Unexpected exception
E/HttpOperation( 6633): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6633): 	at kfv.a(PG:65)
E/HttpOperation( 6633): 	at kff.u(PG:385)
E/HttpOperation( 6633): 	at kfb.a(PG:29)
E/HttpOperation( 6633): 	at ixd.a(PG:248)
E/HttpOperation( 6633): 	at ixd.b(PG:206)
E/HttpOperation( 6633): 	at ixd.a(PG:175)
E/HttpOperation( 6633): 	at fig.a(PG:78)
E/HttpOperation( 6633): 	at lex.a(PG:85)
E/HttpOperation( 6633): 	at lex.b(PG:132)
E/HttpOperation( 6633): 	at fhk.a(PG:1146)
E/HttpOperation( 6633): 	at fhk.a(PG:908)
E/HttpOperation( 6633): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6633): 	at ihi.a(PG:22)
E/HttpOperation( 6633): 	at kft.a(PG:91)
E/HttpOperation( 6633): 	at kfv.a(PG:62)
E/HttpOperation( 6633): 	... 12 more
E/HttpOperation( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6633): 	at gde.c(Unknown Source)
E/HttpOperation( 6633): 	at gde.b(Unknown Source)
E/HttpOperation( 6633): 	at ihi.a(PG:19)
E/HttpOperation( 6633): 	... 14 more
,E/EsSyncAdapterService( 6633): Sync failure
E/EsSyncAdapterService( 6633): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6633): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6633): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6633): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6633): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6633): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6633): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6633): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6633): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6633): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6633): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6633): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6633): 	... 10 more
E/EsSyncAdapterService( 6633): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6633): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6633): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6633): 	... 12 more
E/EsSyncAdapterService( 6633): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6633): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6633): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6633): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6633): 	... 14 more
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1135332, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  873): Explicit concurrent mark sweep GC freed 67225(4MB) AllocSpace objects, 130(2MB) LOS objects, 29% free, 38MB/54MB, paused 2.017ms total 158.494ms
D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 38
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  873): waitForAlarm result :8
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  873): !@Sync 39
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 1050s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  873): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  873): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  873): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  873): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  873): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  873): Updating Usage Statistics in DB @ 1450101407049
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
,W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
,W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
,W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
,W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
,W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  873): ::getAppControlDB: Exception to create DB
,W/System.err(  873): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  873): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  873): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  873): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  873): Done Updating Usage Statistics in DB @ 1450101407303
,E/Watchdog(  873): !@Sync 40
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7318): Starting books sync, d
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1674): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7318): null auth token
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6539405299269983656&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6539405299269983656&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  280): DCD ON
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1674): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  873): uri = 14 selection = getSealedState
,D/SecContentProvider2(  873): mCursor = null
,D/SecContentProvider2(  873): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  873): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  873): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1674): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1674): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1674): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1674): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1674): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7318): Authentication error
E/BooksAccountManager( 7318): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7318): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7318): null auth token
,I/qtaguid ( 7318): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7318, getuid(): 10082
,I/qtaguid ( 7318): Untagging socket 34
,W/ApiaryClient( 7318): Error response from books API: {
W/ApiaryClient( 7318):  "error": {
W/ApiaryClient( 7318):   "errors": [
W/ApiaryClient( 7318):    {
W/ApiaryClient( 7318):     "domain": "global",
W/ApiaryClient( 7318):     "reason": "required",
W/ApiaryClient( 7318):     "message": "Login Required",
W/ApiaryClient( 7318):     "locationType": "header",
W/ApiaryClient( 7318):     "location": "Authorization"
W/ApiaryClient( 7318):    }
W/ApiaryClient( 7318):   ],
W/ApiaryClient( 7318):   "code": 401,
W/ApiaryClient( 7318):   "message": "Login Required"
W/ApiaryClient( 7318):  }
W/ApiaryClient( 7318): }
,W/ApiaryClient( 7318): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6539405299269983656&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7318): Headers suppressed
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7318): Soft error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6539405299269983656&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7318): Sync error
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7318): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6539405299269983656&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7318): Headers suppressed
E/BooksSync( 7318): 
E/BooksSync( 7318): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7318): Finished books sync
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  873): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1237735, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  873): mCursor = null
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  873): !@Sync 41
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 42
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  873): waitForAlarm result :8
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 1155s ago
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 43
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 44
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 45
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 46
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 1265s ago
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 47
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 285, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 48
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 283, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 49
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 281, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 280, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 280, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/TimaService(  873): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  873): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  873): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  873): !@Sync 50
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 281, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 1380s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 282, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 283, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 51
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 284, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  873): !@Sync 52
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 283, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 53
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,E/SMD     (  280): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 54
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 1500s ago
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 55
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 56
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 57
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 58
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,I/PowerManagerService(  873): [PWL] Off : 1625s ago
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  873): !@Sync 59
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,D/NetworkStatsFactory(  873): UpdateStatsForKnox
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/TimaService(  873): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  873): TimaServiceHandler.handleMessage what =1
,D/TimaService(  873): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  873): !@Sync 60
,E/SMD     (  280): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  873): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  873): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,D/BatteryService(  873): stay LED for fully charged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :8
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 290, PST = 274, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  873): SIOP:: AP = 280, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 61
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  873): !@Sync 62
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  873): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,I/PowerManagerService(  873): [PWL] Off : 1755s ago
,E/SMD     (  280): DCD ON
,D/SSRM:m  (  873): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  280): DCD ON
,E/SMD     (  280): DCD ON
,E/Watchdog(  873): !@Sync 63
,E/SMD     (  280): DCD ON
,V/AlarmManager(  873): waitForAlarm result :4
,D/LightsService(  873): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  873): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  873): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ActivityManager(  873): Killing 7734:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7670:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1800s
,D/BatteryService(  873): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  873): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  873): stay LED for fully charged
,I/ActivityManager(  873): Killing 7650:com.android.chrome/u0a88 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 6596:com.sec.chaton/u0a86 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7629:com.sec.knox.bridge/1000 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7611:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 6811:com.osp.app.signin/u0a45 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 6791:com.policydm/1000 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7589:com.sec.android.soagent/u0a37 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7574:com.samsung.klmsagent/u0a19 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7554:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7536:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7510:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 7155:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1800s
,I/ActivityManager(  873): Killing 5389:com.google.android.music:main/u0a126 (adj 15): empty for 1801s
,I/ActivityManager(  873): Killing 6773:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,I/ActivityManager(  873): Killing 7772:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1802s
,I/ActivityManager(  873): Killing 4950:com.android.defcontainer/u0a5 (adj 15): empty for 1836s
,I/ActivityManager(  873): Killing 4778:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1838s
,I/ActivityManager(  873): Killing 6013:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1843s
,I/ActivityManager(  873): Killing 7192:com.sec.android.app.music:service/u0a44 (adj 15): empty for 1843s
,I/ActivityManager(  873): Killing 6254:com.google.android.gm/u0a114 (adj 15): empty for 1843s
,I/ActivityManager(  873): Killing 7109:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1844s
,I/ActivityManager(  873): Killing 6710:com.google.android.gms:car/u0a12 (adj 15): empty for 1844s
I/ActivityManager(  873): Killing 7091:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1844s
,I/ActivityManager(  873): Killing 7055:com.samsung.helphub/1000 (adj 15): empty for 1844s
,I/ActivityManager(  873): Killing 7039:com.samsung.android.magazine.service/u0a118 (adj 15): empty for 1844s
I/ActivityManager(  873): Killing 7022:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): empty for 1844s
,I/ActivityManager(  873): Killing 7005:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1844s
,I/ProcessStatsService(  873): Prepared write state in 10ms
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,V/NetworkStats(  873): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  873): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  873): UpdateStatsForKnox
,D/ConnectivityService(  873): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  873): performPollLocked() took 6ms
,D/NtpTrustedTime(  873): currentTimeMillis() cache hit
,D/BatteryService(  873): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/MotionRecognitionService(  873):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  873): Plugged
,I/MotionRecognitionService(  873): setPowerConnected  = true
,V/HeadsetService( 3245): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3245): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/NtpTrustedTime(  873): currentTimeMillis() cache hit
,D/NtpTrustedTime(  873): currentTimeMillis() cache hit
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1674): Message class com.google.f.a.a.i
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  873): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1674): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1674): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1674): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1674): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1674): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  873): Light old sensor_state 8704, new sensor_state : 8192 en : 0
D/LightsService(  873): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager(  873): unregisterListener ::   
D/LightsService(  873): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/ProcessStatsService(  873): Pruning old procstats: /data/system/procstats/state-2015-12-13-12-29-08.bin
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_6773/cgroup.procs: No such file or directory
,E/SQLiteLog( 1674): (10) POSIX Error : 11 SQLite Error : 3850
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_7005/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10118/pid_7039/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10112/pid_7022/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10166/pid_7091/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_7055/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10012/pid_6710/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10126/pid_5389/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10012/pid_4778/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10170/pid_7109/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10002/pid_7510/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10078/pid_7772/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10114/pid_6254/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10037/pid_7589/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10004/pid_7155/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_7536/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10011/pid_7554/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10019/pid_7574/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_6791/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10045/pid_6811/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10005/pid_4950/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10071/pid_7611/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_7629/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10138/pid_7734/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10048/pid_6013/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10088/pid_7650/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10086/pid_6596/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10044/pid_7192/cgroup.procs: No such file or directory
,W/libprocessgroup(  873): failed to open /acct/uid_10128/pid_7670/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8761): 
D/AndroidRuntime( 8761): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8761): CheckJNI is OFF
D/AndroidRuntime( 8761): setted country_code = Germany
D/AndroidRuntime( 8761): setted countryiso_code = DE
D/AndroidRuntime( 8761): setted sales_code = DBT
D/AndroidRuntime( 8761): readGMSProperty: start
D/AndroidRuntime( 8761): readGMSProperty: already setted!!
D/AndroidRuntime( 8761): readGMSProperty: end
D/AndroidRuntime( 8761): addProductProperty: start
E/SMD     (  280): DCD ON
E/AffinityControl( 8761): AffinityControl: registerfunction enter
D/AndroidRuntime( 8761): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  873): START PACKAGE DELETE: observer{370910961}
D/PackageManager(  873): pkg{<packageName>}
D/PackageManager(  873): user{0}
D/PackageManager(  873): caller{2000}
D/PackageManager(  873): flags{3}
D/PersonaManagerService(  873): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  873): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  873): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  873): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  873): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  873): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  873): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  873): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  873): getApplicationUninstallationEnabled
D/ApplicationPolicy(  873): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  873): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  873): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  873): Killing 7387:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  873):   Force finishing activity ActivityRecord{6525e32 u0 com.test.thalitest/.MainActivity t12}
D/FocusedStackFrame(  873): Set to : 0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/WifiService(  873): Client connection lost with reason: 4
W/PackageSettings(  873): Skipping PackageSetting{3235daa5 com.example.hello/10374} due to missing metadata
D/ConnectivityService(  873): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  873): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 1568): Explicit concurrent mark sweep GC freed 720(42KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 384us total 18.657ms
I/art     ( 4456): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 320us total 22.159ms
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  873): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1864): mOCRHelper is null
W/GeofencerStateMachine( 2222): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8783): MountEmulatedStorage()
I/libpersona( 8783): KNOX_SDCARD checking this for 10019
E/Zygote  ( 8783): v2
I/libpersona( 8783): KNOX_SDCARD not a persona
I/ActivityManager(  873): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8783 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/SSRM:m  (  873): SIOP:: AP = 290, PST = 277, CUR = 300
I/SELinux ( 8783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/TimaKeyStoreProvider( 8783): TimaSignature is unavailable
D/ActivityThread( 8783): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SurfaceWidgetView( 1483): destroyHardwareResources():639908017
V/WindowOrientationListener(  873): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  873): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  873): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  873): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  873): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/Launcher( 1483): onRestart, Launcher: 314533211
D/Launcher( 1483): onStart, Launcher: 314533211
D/Launcher.HomeView( 1483): onStart
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2140): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2140): [237392/6] SurfaceWidget drawing first frame
I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  873): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBarManagerService(  873): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager( 8783): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/KLMS-2.4.503: ( 8783): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/art     (  873): Explicit concurrent mark sweep GC freed 88505(8MB) AllocSpace objects, 250(4MB) LOS objects, 29% free, 38MB/54MB, paused 3.891ms total 288.500ms
D/ResourcesManager(  873): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  873): WaitForGcToComplete blocked for 272.987ms for cause Explicit
I/KLMS-2.4.503: ( 8783): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450102102919
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/RegisteredServicesCache( 1455): empty dynamic service
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/KLMS-2.4.503: ( 8783): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/KLMS-2.4.503: ( 8783): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/SecContentProvider2(  873): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  873): mCursor = null
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/InputMethodManagerService(  873): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/InputMethodManagerService(  873): Got RemoteException sending setActive(false) notification to pid 7387 uid 10367
W/ContextImpl(  873): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/EnterpriseDeviceManagerService(  873): Package has changed for user 0
D/EnterpriseDeviceManagerService(  873): Admin package name: com.google.android.gms
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/Zygote  ( 8811): MountEmulatedStorage()
E/Zygote  ( 8811): v2
I/libpersona( 8811): KNOX_SDCARD checking this for 10104
I/libpersona( 8811): KNOX_SDCARD not a persona
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/ActivityManager(  873): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8811 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  873): Killing 7749:com.android.email/u0a163 (adj 15): empty for 1803s
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/art     (  873): Explicit concurrent mark sweep GC freed 14081(638KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 37MB/53MB, paused 5.616ms total 247.337ms
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/SELinux ( 8811): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/SELinux ( 8811): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8811): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/Timeline(  873): Timeline: Activity_windows_visible id: ActivityRecord{1ede2c08 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1907955
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/libprocessgroup(  873): failed to open /acct/uid_10163/pid_7749/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8811): TimaSignature is unavailable
D/ActivityThread( 8811): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager( 8811): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/PackageManager(  873): delete codoeFile: 
D/elm:14451( 8811): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8811): ELMEngine.ELMEngine( context ).
D/PackageManager(  873): result of delete: 1{370910961}
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/elm:14451( 8811): MDMBridge.setEnterpriseBridge()
D/AndroidRuntime( 8761): Shutting down VM
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/elm:14451( 8811): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/elm:14451( 8811): ElmAgentService : onCreate()
D/elm:14451( 8811): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8811): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8811): MDMBridge.getInstance()
D/elm:14451( 8811): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8828): MountEmulatedStorage()
E/Zygote  ( 8828): v2
I/libpersona( 8828): KNOX_SDCARD checking this for 10017
D/elm:14451( 8811): MDMBridge.getAllLicenseInfoFromSDK()
I/libpersona( 8828): KNOX_SDCARD not a persona
I/ActivityManager(  873): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8828 uid=10017 gids={50017, 9997} abi=armeabi-v7a
I/SELinux ( 8828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/elm:14451( 8811): ElmAgentService : onDestroy().
E/SELinux ( 8828): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  873): Killing 7453:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1803s
D/ResourcesManager(  873): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider( 8828): TimaSignature is unavailable
D/ActivityThread( 8828): Added TimaKeyStore provider
D/ResourcesManager( 8828): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/RCPManagerService(  873): PackageReceiver onReceive()
I/HarmonyEASService(  873): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/libprocessgroup(  873): failed to open /acct/uid_1000/pid_7453/cgroup.procs: No such file or directory
D/KnoxMUMContainerPolicy(  873): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  873): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  873): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  873): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  873): uID is 10367
V/EnterpriseBillingPolicy(  873): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  873): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  873): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  873): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  873): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  873): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  873): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  873): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  873): removeObsoleteFile: deleting file=12_task_thumbnail.png
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8828): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8828): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8828): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Zygote  ( 8844): MountEmulatedStorage()
E/Zygote  ( 8844): v2
I/libpersona( 8844): KNOX_SDCARD checking this for 1000
I/libpersona( 8844): KNOX_SDCARD not a persona
I/ActivityManager(  873): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8844 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  873): Killing 7793:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1803s
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/SELinux ( 8844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/libprocessgroup(  873): failed to open /acct/uid_10178/pid_7793/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8844): TimaSignature is unavailable
D/ActivityThread( 8844): Added TimaKeyStore provider
W/ResourcesManager(  873): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  873): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  873): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8844): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/PCWCLIENTTRACE_LOG( 8844): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8844): DEFAULT_LOGLEVEL : 3
D/ResourcesManager(  873): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
I/PCWCLIENTTRACE_DMDBOpenHelper( 8844): new DMDBOpenHelper instance
D/ResourcesManager(  873): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
I/PCWCLIENTTRACE_PushUtil( 8844): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 8844): sales region : global
I/PCWCLIENTTRACE_PushUtil( 8844): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 8844): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/Zygote  ( 8860): MountEmulatedStorage()
E/Zygote  ( 8860): v2
I/libpersona( 8860): KNOX_SDCARD checking this for 10034
I/libpersona( 8860): KNOX_SDCARD not a persona
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
I/ActivityManager(  873): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8860 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  873): Killing 5152:com.sec.spp.push/u0a38 (adj 15): empty for 1800s
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 8860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  873): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
I/SELinux ( 8860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  873): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 8860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbSettingsManager(  873): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  873): onPackageRemoved : com.test.thalitest
W/libprocessgroup(  873): failed to open /acct/uid_10038/pid_5152/cgroup.procs: No such file or directory
I/EventHub(  873): Removing device '/dev/input/event4' due to inotify event
D/TimaKeyStoreProvider( 8860): TimaSignature is unavailable
D/ActivityThread( 8860): Added TimaKeyStore provider
I/EventHub(  873): Removing device '/dev/input/event5' due to inotify event
D/ResourcesManager( 8860): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/ContextImpl( 8860): Unable to create files subdir /data/data/com.samsung.android.app.galaxyfinder/cache
E/ActivityThread( 8860): Unable to setupGraphicsSupport due to missing cache directory
I/FeatureConfig( 8860): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
I/EventHub(  873): Removing device '/dev/input/event6' due to inotify event
F/libc    ( 8860): Fatal signal 7 (SIGBUS), code 2, fault addr 0x719b1e98 in tid 8860 (pp.galaxyfinder)
E/audit_log( 2171): File locking failed. error= Bad file number
E/audit_log( 2171): File locking failed. error= Bad file number
I/EventHub(  873): Removing device '/dev/input/event7' due to inotify event
I/ActivityManager(  873): Process com.samsung.android.app.galaxyfinder (pid 8860)(adj 0) has died(354,569)
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  873): checkUser: useridlist=null, currentuser=0
I/EventHub(  873): Removing device '/dev/input/event8' due to inotify event
E/Zygote  ( 8877): MountEmulatedStorage()
E/Zygote  ( 8877): v2
I/libpersona( 8877): KNOX_SDCARD checking this for 10035
I/libpersona( 8877): KNOX_SDCARD not a persona
I/ActivityManager(  873): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8877 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/Zygote  (  310): Process 8860 exited due to signal (7)
I/EventHub(  873): Removing device '/dev/input/event9' due to inotify event
I/SELinux ( 8877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8877): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/EventHub(  873): Removing device '/dev/input/event10' due to inotify event
I/EventHub(  873): Removing device '/dev/input/event11' due to inotify event
D/TimaKeyStoreProvider( 8877): TimaSignature is unavailable
D/ActivityThread( 8877): Added TimaKeyStore provider
D/ResourcesManager( 8877): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ContextImpl( 8877): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 8877): Unable to setupGraphicsSupport due to missing cache directory

```
