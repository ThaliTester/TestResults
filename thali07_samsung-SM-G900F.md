#### Test 558973767bac5c9_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7345): null auth token
I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
I/qtaguid ( 7345): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
I/qtaguid ( 7345): Untagging socket 34
W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
W/ApiaryClient( 7345): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6951583046826098115&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
--------- beginning of system
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SMD     (  288): DCD ON
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7345): null auth token
I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
D/AndroidRuntime( 7391): 
D/AndroidRuntime( 7391): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7391): CheckJNI is OFF
D/AndroidRuntime( 7391): setted country_code = Germany
D/AndroidRuntime( 7391): setted countryiso_code = DE
D/AndroidRuntime( 7391): setted sales_code = DBT
D/AndroidRuntime( 7391): readGMSProperty: start
D/AndroidRuntime( 7391): readGMSProperty: already setted!!
D/AndroidRuntime( 7391): readGMSProperty: end
D/AndroidRuntime( 7391): addProductProperty: start
I/qtaguid ( 7345): Untagging socket 34
W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
W/ApiaryClient( 7345): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6951583046826098115&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/AffinityControl( 7391): AffinityControl: registerfunction enter
D/AndroidRuntime( 7391): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  849): inState():  stateMachine is null !!
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  849): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  849): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  849): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  849): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3565): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3565): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 56
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/AndroidRuntime( 7391): Shutting down VM
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  849): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 849) 
D/LightsService(  849): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  849): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  849): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
I/PhoneStatusBar( 1172): Icon Only
D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  849): showStatusBarByNotification() mOpenByNotification=false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
I/DBG_DM  ( 3769): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3769): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7420): MountEmulatedStorage()
E/Zygote  ( 7420): v2
I/libpersona( 7420): KNOX_SDCARD checking this for 10200
I/libpersona( 7420): KNOX_SDCARD not a persona
V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/ActivityManager(  849): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7420 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
I/SELinux ( 7420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7420): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1172): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3e846fbb
D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1172): Icon Only
D/TimaKeyStoreProvider( 7420): TimaSignature is unavailable
D/ActivityThread( 7420): Added TimaKeyStore provider
V/ActivityManager(  849): Display changed displayId=0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  849): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/PanelView( 1172): There is/are notification(s) 
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager( 7420): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/WebViewFactory( 7420): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7420): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/LibraryLoader( 7420): Loading: webviewchromium
,I/LibraryLoader( 7420): Time to load native libraries: 1 ms (timestamps 6133-6134)
,I/LibraryLoader( 7420): Expected native library version number "",actual native library version number ""
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/WebViewChromiumFactoryProvider( 7420): Binding Chromium to main looper Looper (main, tid 1) {224ddab4}
,I/LibraryLoader( 7420): Expected native library version number "",actual native library version number ""
,I/chromium( 7420): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7420): Initializing chromium process, renderers=0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/art     ( 7420): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7420): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7420): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7420): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Adreno-EGL( 7420): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7420): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7420): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7420): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7420): Remote Branch: 
I/Adreno-EGL( 7420): Local Patches: 
I/Adreno-EGL( 7420): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/chromium( 7420): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7420): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7420): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7420): onDetachedFromWindow called when already detached. Ignoring
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SystemWebViewEngine( 7420): CordovaWebView is running on device made by: samsung
,E/BooksSync( 7345): Soft error
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6951583046826098115&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7345): Headers suppressed
E/BooksSync( 7345): 
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7345): Sync error
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6951583046826098115&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7345): Headers suppressed
E/BooksSync( 7345): 
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7345): Finished books sync
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SyncManager(  849): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63791, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/art     ( 7420): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7420): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  849): Killing 5073:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  849): mCursor = null
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/libprocessgroup(  849): failed to open /acct/uid_10046/pid_5073/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/Activity( 7420): performCreate Call secproduct feature valuefalse
D/Activity( 7420): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/OpenGLRenderer( 7420): Render dirty regions requested: true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ActivityManager(  849): post active user change for 0
D/KnoxTimeoutHandler(  849): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  849): handleActiveUserChange for user 0
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
I/OpenGLRenderer( 7420): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7420): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7420): Enabling debug mode 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/InputMethodManagerService(  849): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,E/Adreno-ES20( 7420): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7420): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  849): Displayed com.test.thalitest/.MainActivity: +687ms
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline( 7420): Timeline: Activity_idle id: android.os.BinderProxy@3beb0477 time:96599
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/JsMessageQueue( 7420): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/chromium( 7420): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7420): 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/CustomFrequencyManagerService(  849): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  849): mDVFSHelper.release()
I/Timeline(  849): Timeline: Activity_windows_visible id: ActivityRecord{8be4056 u0 com.test.thalitest/.MainActivity t18} time:96733
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/CustomFrequencyManagerService(  849): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/GAV2    ( 7345): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/jxcore_app_log( 7420): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358536704
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,I/chromium( 7420): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager(  849): waitForAlarm result :4
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7477): MountEmulatedStorage()
E/Zygote  ( 7477): v2
I/libpersona( 7477): KNOX_SDCARD checking this for 10179
I/libpersona( 7477): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7477 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,D/CustomFrequencyManagerService(  849): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  tag : ACTIVITY_RESUME_BOOSTER@10
,I/SELinux ( 7477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/TimaKeyStoreProvider( 7477): TimaSignature is unavailable
,D/ActivityThread( 7477): Added TimaKeyStore provider
,D/ResourcesManager( 7477): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 7477): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/UMC:Core( 7477): onCreate(): 
,D/USER_AGENT( 7477): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,D/[SAMSUNG SMARCART NATIVE]( 7477): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 7477): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7477): ================================================
,I/CSTORAGE( 7477):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7477): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7477): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7477): FINISHED: initialize rv:0
,D/UMC:SecurityUtils( 7477): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7477): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7477): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7477): New Flow
,D/TimaService(  849): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService(  849): TIMA: in getTimaVersion
I/        (  849): CCM JNI: In ccm_register_for_default_cert
I/        (  849): CCM JNI: In ccm_create_slot
,I/TZ_CCM_C_Initialize: (  849): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  849): pInitArgs 0xb3cc7814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  849): &ctx = 0x9feb2c1c
I/TLC_TZ_CCM: (  849): creating new ccm context...
I/TLC_TZ_CCM: (  849): initializing ccm context...
,I/TLC_TZ_CCM: (  849): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  849): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  849): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  849): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  849): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  849): process = tz_ccm, process_strlen = 6
,I/TZ: client_server_communication(  849): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  849): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  849): Client_Server_Open was called
,I/TZ: client_server_communication(  849): IClientServer::IClientServer()
I/TZ: client_server_communication(  849): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  849): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1079): OPENSWCONN
I/TZ_CCM_SERVER( 1079): creating new ccm context...
I/TZ_CCM_SERVER( 1079): initializing ccm context...
I/TZ_CCM_SERVER( 1079): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1079): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1079): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1079): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1079): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1079): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1079): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1079): QSEECom_get_handle sb_length = 0x9800
,D/QSEECOMAPI: ( 1079): App is not loaded in QSEE
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QSEECOMAPI: ( 1079): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication( 1079): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  849): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  849): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  849): ctx = 0x93a04d90, comm = 0x94103ad8, sendmsg = 0x93a9f000, recvmsg = 0x93aa3c00
I/TZ_init: (  849): TZ_init: sending initialization request...
,I/TZ: client_server_communication(  849): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  849): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
,I/TZ_init: (  849): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: (  849): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  849): Cmd id = 17, len = 19456
,I/TZ: client_server_communication(  849): Calling Communicate()
,I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
,I/TZ_COMMON: tlc_key_db_util: (  849): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: (  849): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  849): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  849): Calling Communicate()
,I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
,I/TLC_TZ_CCM: register for default cert: (  849): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  849): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  849): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  849): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  849): Calling Communicate()
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1079): COMM
,I/TZ: client_server_communication(  849): Client_Server_Close was called
I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/TZ_CCM_SERVER( 1079): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1079): CLOSESWCONN
D/QSEECOMAPI: ( 1079): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1079): QSEECom_shutdown_app, app_id = 3
,I/TZ: client_server_communication(  849): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7477): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7477): TIMA service call for password change success!!
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UMC:AdminManager( 7477): init - start
,D/UMC:AdminManager( 7477): loadAdmins
,D/Finsky  ( 6583): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6583): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6583): [1] 5.onFinished: Scheduling replication attempt 2.
,D/UMC:AdminManager( 7477): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7477): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7477): init - end
,V/UMC:AlarmHandler( 7477): Enter loadList
,D/GSLBManager( 7477): migrateStoredUrlFromOldPref
,D/GSLBManager( 7477): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7477): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7477): Admin not found in package com.samsung.knoxpb.mdm
,D/UMC:UMCAdmin( 7477): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7477): isContainer : 0
,W/LicenseLogService(  849): log() failed
,D/EnterpriseDeviceManagerService(  849): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7477): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7477): isContainer : 0
,D/UMC:UMCAdmin( 7477): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7477): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/QuickStartReceiver( 7477): Msg Id : 2
,D/QuickStartReceiver( 7477): model : SM-G900F
D/QuickStartReceiver( 7477): id : 100
,I/ActivityManager(  849): Killing 6690:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,E/SMD     (  288): DCD ON
,W/libprocessgroup(  849): failed to open /acct/uid_10054/pid_6690/cgroup.procs: No such file or directory
,D/PowerManagerService(  849): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1172 (0x0)
,W/jxcore-log( 7420): Initializing JXcore engine
W/jxcore-log( 7420): JXcore engine is ready
,E/auditd  ( 2010): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  849): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  849): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7505): MountEmulatedStorage()
,E/Zygote  ( 7505): v2
I/libpersona( 7505): KNOX_SDCARD checking this for 1000
I/libpersona( 7505): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7505 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/jxcore-log( 7420): Starting JXcore engine
,I/SELinux ( 7505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7505): TimaSignature is unavailable
,D/ActivityThread( 7505): Added TimaKeyStore provider
D/ResourcesManager( 7505): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
W/jxcore-log( 7420): Platform android
W/jxcore-log( 7420): 
W/jxcore-log( 7420): Process ARCH arm
W/jxcore-log( 7420): 
,D/SecurityLogAgent( 7505):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7505):  SeDenialReceiver : File path = null
,I/ActivityManager(  849): Killing 5865:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_5865/cgroup.procs: No such file or directory
,I/jxcore-log( 7420): JXcore Cordova bridge is ready!
I/jxcore-log( 7420): 
,W/jxcore-log( 7420): JXcore engine is started
,I/jxcore-log( 7420): Toggling radios to true
I/jxcore-log( 7420): 
,D/BluetoothAdapter( 7420): enable()
,D/BluetoothAdapter( 7420): enable(): BT is already enabled..!
,D/WifiService(  849): New client listening to asynchronous messages
,I/WifiManager( 7420): packageName : com.test.thalitest
,D/SecContentProvider(  849): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  849): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  849): mCursor = null
,D/WifiService(  849): setWifiEnabled: true pid=7420, uid=10200
E/WifiService(  849): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  849): Permission Denial: getCurrentUser() from pid=7420, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,D/SSRM:m  (  849): SIOP:: AP = 380, PST = 419, CUR = 300
,W/WifiService(  849): Failed getting userId using ActivityManagerNative
W/WifiService(  849): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7420, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  849): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  849): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  849): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  849): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  849): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  849): name = wifi_on
,I/WifiService(  849): disconnect: pid=7420, uid=10200
,I/wpa_supplicant( 1285): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7420): Radios toggled
I/jxcore-log( 7420): 
,I/jxcore-log( 7420): My device name is: samsung-SM-G900F
I/jxcore-log( 7420): 
,I/wpa_supplicant( 1285): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1285): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1285): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  849): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1285): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1285): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1285): Disconnected - do not scan
I/wpa_supplicant( 1285): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  849): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  849): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  849): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  849): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  849): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  849): InactiveState{ what=143375 }
,D/WifiP2pService(  849): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  283): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1772): Read error: ssl=0xaf335e00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  849): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  849): updateNetworkInfo()
D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  849): evaluateTrafficStatsPolling
,I/CLocInfoService(  849): External Intent Received android.net.wifi.STATE_CHANGE
,V/NativeCrypto( 1772): SSL shutdown failed: ssl=0xaf335e00: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/WifiConfigStore(  849): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): DefaultState{ when=-3ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): EvaluatingState{ when=-3ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): Validated
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  849): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1285): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1285): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1285): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1285): First Scan Start
,I/wpa_supplicant( 1285): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  849): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  849): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  849): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  849): InactiveState{ what=143375 }
,D/WifiP2pService(  849): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1302): Starting #6
I/Hs20UtilService( 1302): Message received 5007
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  849): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  849): calling update connectivity
D/CommandListener(  283): Clearing all IP addresses on wlan0
,D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  849): Not allowed due to - mEnabled false
D/ConnectivityService(  849): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
,E/WifiStateMachine(  849): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  849): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): Disconnected - quitting
,D/WifiStateMachine(  849): updateConfiguredNetworkExpiration - currTime: 1452693146707
,I/WifiTrafficPoller(  849): evaluateTrafficStatsPolling
,D/ConnectivityService(  849): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiStateMachine(  849): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/TelephonyNetworkFactory( 1468): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/CLocInfoService(  849): External Intent Received android.net.wifi.STATE_CHANGE
D/CSLegacyTypeTracker(  849): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  849): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/WifiStateMachine(  849): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  849): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  849): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiNetworkAgent(  849): NetworkAgent: NetworkAgent channel lost
,I/Hs20UtilService( 1302): Starting #7
,I/Hs20UtilService( 1302): Message received 5007
D/SmartBondingService(  849): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  849): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  849): getSBEnabled() enabled =false
D/SmartBondingService(  849): getSBEnabled() enabled =false
D/SmartBondingService(  849): getSBEnabled() enabled =false
E/ConnectivityService(  849): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,V/NetworkStats(  849): updateIfacesLocked()
,E/ConnectivityService(  849): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
V/NetworkStats(  849): performPollLocked(flags=0x1)
,D/NtpTrustedTime(  849): currentTimeMillis() cache hit
D/SmartBondingService(  849): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  849): UpdateStatsForKnox
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  849): currentTimeMillis() cache hit
,D/NtpTrustedTime(  849): currentTimeMillis() cache hit
,D/NtpTrustedTime(  849): currentTimeMillis() cache hit
V/NetworkStats(  849): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
,E/WifiStateMachine(  849): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  849): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  849): setDetailed state send new extra info"NG700"
,V/NetworkStats(  849): performPollLocked() took 10ms
,D/NtpTrustedTime(  849): currentTimeMillis() cache hit
,D/SecContentProvider2(  849): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  849): mCursor = null
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime(  849): currentTimeMillis() cache hit
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
,D/SecContentProvider2(  849): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  849): mCursor = null
,D/TaskPersister(  849): removeObsoleteFile: deleting file=17_task_thumbnail.png
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  849): updateDataUsageMap
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7173): [#DCM#] [DCM_Performance] onReceive completed in time  237 microsec. 
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  849): MasterInitialState.processMessage what=3
,D/SmartBondingService(  849): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  849): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  849): getSBEnabled() enabled =false
D/SmartBondingService(  849): getSBEnabled() enabled =false
D/SmartBondingService(  849): getSBEnabled() enabled =false
,I/CLocInfoService(  849): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  849): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  849): CLoinfo wifi false
,W/SLocation(  849): No Active Data Connection
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5337): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6796): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6796): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6796): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6796): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6796): noConnectivity : true
,I/DBG_DM  ( 3769): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3769): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 7173): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7173): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7173): [#DCM#] setIsConnectedForExtractors 
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7561): MountEmulatedStorage()
,E/Zygote  ( 7561): v2
I/libpersona( 7561): KNOX_SDCARD checking this for 10002
,I/libpersona( 7561): KNOX_SDCARD not a persona
,I/SELinux ( 7561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7561): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  849): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7561 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  316): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 282us total 23.291ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 281us total 8.311ms
,D/TimaKeyStoreProvider( 7561): TimaSignature is unavailable
,D/ActivityThread( 7561): Added TimaKeyStore provider
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 283us total 8.682ms
,D/ResourcesManager( 7561): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  849): Killing 6214:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7587): MountEmulatedStorage()
I/libpersona( 7587): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7587): v2
I/libpersona( 7587): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7587 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7587): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7587): TimaSignature is unavailable
,D/ActivityThread( 7587): Added TimaKeyStore provider
,D/ResourcesManager( 7587): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  849): failed to open /acct/uid_10168/pid_6214/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7587): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7587): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7587): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7587): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7607): MountEmulatedStorage()
,E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 10011
I/libpersona( 7607): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7607 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 1285): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1285): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1285): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1285): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  849): [1,452,693,147,779 ms] noteScanEnd no scan source
,E/WifiStateMachine(  849): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3b8e2444 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  849): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  849): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  849): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  849): setDetailed state send new extra info0x
,D/SecContentProvider2(  849): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  849): mCursor = null
,D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
,D/ActivityThread( 7607): Added TimaKeyStore provider
,D/ResourcesManager( 7607): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  849): Killing 6752:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/FOTA_Client( 7607): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7607): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1285): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1285): Associated with C0.AA.48
,E/WifiStateMachine(  849): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  849): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/FOTA_Client( 7607): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/SecContentProvider2(  849): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  849): mCursor = null
,I/FOTA_Client( 7607): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7607): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1285): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  849): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  849): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  849): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  849): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  849): mCursor = null
,I/wpa_supplicant( 1285): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/libpersona( 7626): KNOX_SDCARD checking this for 10019
E/Zygote  ( 7626): MountEmulatedStorage()
I/libpersona( 7626): KNOX_SDCARD not a persona
E/Zygote  ( 7626): v2
,I/wpa_supplicant( 1285): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1285): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1285): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1285): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1285): Blacklist: Clear (temp) 
I/wpa_supplicant( 1285): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/ActivityManager(  849): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7626 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 6773:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/WifiStateMachine(  849): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  849): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  849): Network connection established
,D/WifiNative-HAL(  849): callSECApiVoid - ID [50]
E/WifiStateMachine(  849): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  849): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  849): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  849): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  849): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  849): Got NetworkAgent Messenger
D/ConnectivityService(  849): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  849): updateNetworkInfo()
D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  849): NetworkAgent connected
E/WifiStateMachine(  849): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  849): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SELinux ( 7626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/SELinux ( 7626): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  849): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  849): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  849): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  849): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  283): Setting iface cfg
,E/WifiStateMachine(  849): Start Dhcp Watchdog 2
,D/SecContentProvider2(  849): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  849): mCursor = null
,D/TimaKeyStoreProvider( 7626): TimaSignature is unavailable
,D/ActivityThread( 7626): Added TimaKeyStore provider
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  849): calculateWifiScore() report new score 60
I/WifiStateMachine(  849): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  849): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,D/ConnectivityService(  849): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,D/ResourcesManager( 7626): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
E/WifiStateMachine(  849): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  849): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/libprocessgroup(  849): failed to open /acct/uid_10015/pid_6752/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7626): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7626): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452693147973
,I/KLMS-2.4.503: ( 7626): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7626): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7626): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  849): Killing 6445:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7645): MountEmulatedStorage()
,E/Zygote  ( 7645): v2
I/libpersona( 7645): KNOX_SDCARD checking this for 10037
I/libpersona( 7645): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7645 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,E/SMD     (  288): DCD ON
,I/SELinux ( 7645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/WifiStateMachine(  849): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,I/SELinux ( 7645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/native  (  849): do suspend false
,E/SELinux ( 7645): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  849): failed to open /acct/uid_10016/pid_6773/cgroup.procs: No such file or directory
,D/SecContentProvider2(  849): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  849): mCursor = null
,D/WifiP2pService(  849): InactiveState{ what=143375 }
D/WifiP2pService(  849): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7645): TimaSignature is unavailable
,D/ActivityThread( 7645): Added TimaKeyStore provider
,D/ResourcesManager( 7645): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7645): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  849): failed to open /acct/uid_10034/pid_6445/cgroup.procs: No such file or directory
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5166): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6831): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6831): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6831): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6831): [SLFUCHKMGR] constructor called
,I/SA      ( 6831): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6831): [OR] == isSIMCardReady false ==
,I/SA      ( 6831): [SCU] == networkStateCheck == false
I/SA      ( 6831): [OR] onReceive END
,E/SPPClientService( 5166): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7662): MountEmulatedStorage()
E/Zygote  ( 7662): v2
I/libpersona( 7662): KNOX_SDCARD checking this for 10071
I/libpersona( 7662): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7662 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  849): Killing 4684:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7662): TimaSignature is unavailable
,D/ActivityThread( 7662): Added TimaKeyStore provider
,D/ResourcesManager( 7662): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7662): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7662): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7662): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7662): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7662): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7662): [KK AccuPhone]>>> ==============================================================================================
,E/dhcpcd  ( 7677): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/comsamsunglog( 7662): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7662): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7662): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7662): [KK AccuPhone]>>> ==============================================================================================
,I/dhcpcd  ( 7677): version 5.5.6 starting
,D/SettingsProvider(  849): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  849): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  849): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  849): selectionArgs: false
D/SettingsProvider(  849): selectionArgs: 10071
D/SecContentProvider(  849): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  849): ret = -1
,E/dhcpcd  ( 7677): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/daemonapp( 1371): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7662): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7662): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7662): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7662): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7662): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7662): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1371): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7662): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1371): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7662): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1371): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  849): failed to open /acct/uid_10035/pid_4684/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7677): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7677): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7677): bssid match
D/accuweather( 7662): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
D/accuweather( 7662): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/dhcpcd  ( 7677): wlan0: rebinding lease of 192.168.1.135
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7686): MountEmulatedStorage()
,E/Zygote  ( 7686): v2
I/libpersona( 7686): KNOX_SDCARD checking this for 1000
I/libpersona( 7686): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7686 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 6039:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7686): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7686): TimaSignature is unavailable
,D/ActivityThread( 7686): Added TimaKeyStore provider
,D/ResourcesManager( 7686): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/libprocessgroup(  849): failed to open /acct/uid_10042/pid_6039/cgroup.procs: No such file or directory
,W/ResourcesManager( 7686): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7686): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7686): premStatus:2
,I/KnoxUsageLogPro( 7686): isEulaShown : false
I/KnoxUsageLogPro( 7686): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7701): MountEmulatedStorage()
,E/Zygote  ( 7701): v2
I/libpersona( 7701): KNOX_SDCARD checking this for 10088
I/libpersona( 7701): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7701 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 5680:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/CountryDetector(  849): No listener is left
,I/SELinux ( 7701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7701): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7701): TimaSignature is unavailable
,D/ActivityThread( 7701): Added TimaKeyStore provider
,D/ResourcesManager( 7701): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  849): failed to open /acct/uid_10050/pid_5680/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7677): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/ActivityManager(  849): Killing 6856:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5480): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5480): getCountryCode(): countryCode = DE
,D/Headlines( 5480): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5480): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5480): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5480): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7720): MountEmulatedStorage()
I/libpersona( 7720): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7720): v2
I/libpersona( 7720): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7720 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7677): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  849): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  849): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7720): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  849): failed to open /acct/uid_10051/pid_6856/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7720): TimaSignature is unavailable
,D/ActivityThread( 7720): Added TimaKeyStore provider
,D/ResourcesManager( 7720): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/WifiStateMachine(  849): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  849): InactiveState{ what=143375 }
,D/WifiP2pService(  849): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  849): WifiStateMachine DHCP successful
,E/WifiStateMachine(  849): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  849): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  849): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  849): Not connected state, yet.
E/WifiStateMachine(  849): VerifyingLinkState enter
,D/WifiStateMachine(  849): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  849): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  849): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  849): callSECApiInt - ID [210]
,E/WifiStateMachine(  849): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  849): updateNetworkInfo()
,D/ConnectivityService(  849): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  849): Adding iface wlan0 to network 503
,I/CLocInfoService(  849): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  849): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  849): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  849): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  849): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  849): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  849): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  849): Now, connected state.
E/WifiStateMachine(  849): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/WifiTrafficPoller(  849): evaluateTrafficStatsPolling
I/CLocInfoService(  849): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  849): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/WifiTrafficPoller(  849): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  849): mBoosterFLAG : 0
I/WifiTrafficPoller(  849): current booster mode : FullMode
E/WifiStateMachine(  849): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiNative-HAL(  849): callSECApiVoid - ID [212]
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/CLocInfoService(  849): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  849): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine(  849): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  849): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/WifiStateMachine(  849): REQUEST_POWER_SAVE_ON
D/ConnectivityService(  849): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService(  849): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  849): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  849): updateSourceRoutes : add src route for:192.168.1.135
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
V/        (  283): QcRouteController
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/        (  283): QcRouteController
V/        (  283): QcRouteController
V/        (  283): QcRouteController
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7720): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7720): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/        (  283): QcRouteController
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7720): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,V/        (  283): QcRouteController
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,V/        (  283): QcRouteController
W/ContextImpl( 7720): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/        (  283): QcRouteController
,D/ConnectivityService(  849): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  849): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  849): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  849): calling update connectivity
D/ConnectivityService(  849): ignoring duplicate network state non-change
E/ConnectivityService(  849): updateNetworkInfo()
D/ConnectivityService(  849): ignoring duplicate network state non-change
,E/ConnectivityService(  849): updateNetworkInfo()
D/ConnectivityService(  849): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  849): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  849): calling update connectivity
,D/ConnectivityService(  849): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  849): Validated
D/ConnectivityService(  849):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  849):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  849): currentScore = 0, newScore = 60
D/ConnectivityService(  849):    accepting network in place of null
D/ConnectivityService(  849): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1468): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  849): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  849): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  849): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  849): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  849): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity(  849): Not allowed due to - mEnabled false
D/ConnectivityService(  849): calling update connectivity
,D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/ConnectivityService(  849): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  849):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  849):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  849): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService(  849): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  849): calling update connectivity
,D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,W/ProcessCpuTracker(  849): Skipping unknown process pid 7784
W/ProcessCpuTracker(  849): Skipping unknown process pid 7785
,D/SmartBondingService(  849): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  849): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  849): getSBEnabled() enabled =false
V/NetworkStats(  849): updateIfacesLocked()
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
V/NetworkStats(  849): performPollLocked(flags=0x1)
D/SmartBondingService(  849): getSBEnabled() enabled =false
,D/SmartBondingService(  849): getSBEnabled() enabled =false
D/NetworkStatsFactory(  849): UpdateStatsForKnox
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  849): performPollLocked() took 3ms
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
,D/SmartBondingService(  849): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
V/NetworkStats(  849): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
D/NtpTrustedTime(  849): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WebViewFactory( 7720): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7720): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7720): Loading: webviewchromium
,I/LibraryLoader( 7720): Time to load native libraries: 4 ms (timestamps 1683-1687)
I/LibraryLoader( 7720): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7720): Binding Chromium to main looper Looper (main, tid 1) {30fc6112}
,I/LibraryLoader( 7720): Expected native library version number "",actual native library version number ""
,I/chromium( 7720): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7720): Initializing chromium process, renderers=0
,W/art     ( 7720): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7720): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7720): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7720): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7720): Requires BLUETOOTH permission
,I/Adreno-EGL( 7720): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7720): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7720): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7720): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7720): Remote Branch: 
I/Adreno-EGL( 7720): Local Patches: 
I/Adreno-EGL( 7720): Reconstruct Branch: 
,I/NSApplication( 7720): Starting up...
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7819): MountEmulatedStorage()
,E/Zygote  ( 7819): v2
I/libpersona( 7819): KNOX_SDCARD checking this for 10138
I/libpersona( 7819): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7819 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 6872:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7819): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7819): TimaSignature is unavailable
,D/ActivityThread( 7819): Added TimaKeyStore provider
,D/ResourcesManager( 7819): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/libprocessgroup(  849): failed to open /acct/uid_10058/pid_6872/cgroup.procs: No such file or directory
,W/ResourcesManager( 7819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7819): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7819): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7819): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7819): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7819): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7835): MountEmulatedStorage()
,E/Zygote  ( 7835): v2
I/libpersona( 7835): KNOX_SDCARD checking this for 10163
I/libpersona( 7835): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7835 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 6233:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7835): TimaSignature is unavailable
,D/ActivityThread( 7835): Added TimaKeyStore provider
,D/ResourcesManager( 7835): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7835): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7835): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7835): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7835): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityService(  849): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SmartBondingService(  849): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  849): MasterInitialState.processMessage what=3
D/SmartBondingService(  849): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  849): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  849): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  849): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  849): getSBEnabled() enabled =false
,D/SmartBondingService(  849): getSBEnabled() enabled =false
D/SmartBondingService(  849): getSBEnabled() enabled =false
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  849): CLocinfo wifi true 
D/SmartBondingService(  849): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2044): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2044): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_6233/cgroup.procs: No such file or directory
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  849): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  849): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  849): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  849): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  849): identical MTU - not setting
D/ConnectivityService(  849): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  849): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  283): QcRouteController
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  283): QcRouteController
I/SystemBroadcastReceiver( 7173): [#DCM#] [DCM_Performance] onReceive completed in time  195 microsec. 
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3769): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/NetworkManagementService(  849): route cmd failed: 
W/NetworkManagementService(  849): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  849): '
W/NetworkManagementService(  849): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  849): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  849): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  849): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  849): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  849): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  849): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  849): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  849): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  849): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  849): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DBG_DM  ( 3769): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/Nat464Xlat(  849): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  849): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  849): calling update connectivity
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  849): calling update connectivity
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  849):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  849): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7173): [#DCM#] Calling notifyListeners. 
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5337): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DCMController( 7173): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7173): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  849): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  849): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  849): getSBEnabled() enabled =false
,D/SmartBondingService(  849): getSBEnabled() enabled =false
D/SmartBondingService(  849): getSBEnabled() enabled =false
,I/DatabaseRebuilderTask( 7173): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,I/art     (  849): Explicit concurrent mark sweep GC freed 71624(3MB) AllocSpace objects, 11(1586KB) LOS objects, 29% free, 37MB/53MB, paused 1.408ms total 105.674ms
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  849): mCursor = null
,I/FrameworkService( 7173): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7173): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7173): [#DCM#] getSuccessState = true
I/FrameworkService( 7173): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7173): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,I/SystemUtils( 7173): [#DCM#] LM: false,AM:619589632
,I/DCMThreadPoolExecutor( 7173): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7173): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@ad4c314 is submitted
I/FrameworkService( 7173): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 20464 mirosec. 
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,I/DatabaseRebuilderTask( 7173): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7173): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7173): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,I/DatabaseRebuilderTask( 7173): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7173): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7173): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7173): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7173): [#DCM#] setHeavySharedPref set as  false
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,I/IntentHandler( 7173): [#DCM#] Stopping service with ids up to  1
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,E/Zygote  ( 7864): MountEmulatedStorage()
,E/Zygote  ( 7864): v2
I/libpersona( 7864): KNOX_SDCARD checking this for 10078
I/libpersona( 7864): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7864 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,I/DCMThreadPoolExecutor( 7173): [#DCM#] afterExecute FutureTask
,I/DCMController( 7173): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@ad4c314
,D/PowerManagerService(  849): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  849): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  849): [s] DisplayPowerCallbacks : onStateChanged()
,I/art     (  316): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 14.776ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.738ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.488ms
,I/SELinux ( 7864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7864): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,D/DisplayPowerController(  849): getFinalBrightness : 1 -> 1
,D/lights  (  849): lcd : 1 +
,D/lights  (  849): lcd : 1 -
,D/DisplayPowerController(  849): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7505): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7505): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7505): StateMachine : Current State = 1
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7505): StateMachine : Changed Current State = 1
,I/ActivityManager(  849): Killing 6893:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/TimaKeyStoreProvider( 7864): TimaSignature is unavailable
,D/ActivityThread( 7864): Added TimaKeyStore provider
,I/ActivityManager(  849): Killing 6943:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5586): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): last run: 1452672209054 -- System.currentTimeMillis()-last_run: 20940852
D/com.peel.receiver.ConnectivityActionReceiver( 5586): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): ... skip last_72_check
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7864): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/Zygote  ( 7880): MountEmulatedStorage()
E/Zygote  ( 7880): v2
I/libpersona( 7880): KNOX_SDCARD checking this for 10178
I/libpersona( 7880): KNOX_SDCARD not a persona
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,I/ActivityManager(  849): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7880 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,I/SELinux ( 7880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,I/SELinux ( 7880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
E/SELinux ( 7880): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,D/BadgeProvider( 7864): onCreate
D/BadgeProvider( 7864): DatabaseHelper
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,D/TimaKeyStoreProvider( 7880): TimaSignature is unavailable
,D/ActivityThread( 7880): Added TimaKeyStore provider
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/BadgeProvider( 7864): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/ResourcesManager( 7880): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/BadgeProvider( 7864): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1487): reloadBadges entered.
D/BadgeProvider( 7864): sendNotify, [notify] : null
D/BadgeProvider( 7864): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7864): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7864): update, [UpdateCount] : 1
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,W/libprocessgroup(  849): failed to open /acct/uid_10098/pid_6893/cgroup.procs: No such file or directory
,W/libprocessgroup(  849): failed to open /acct/uid_10033/pid_6943/cgroup.procs: No such file or directory
I/ActivityManager(  849): Killing 6921:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7835): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  849): failed to open /acct/uid_10099/pid_6921/cgroup.procs: No such file or directory
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,D/WaitQueueForNetworkActivate( 7146): notifyNetworkActivated
I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
,D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2475): [AccountUtils] Account not ready
W/Kids    ( 2475): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2475): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2475): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2475): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2475): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2475): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/ContextImpl( 7146): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  849): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager(  849): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/hcjo    ( 7146): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7146): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7146): exit::IDLE
D/InitializeManagerStateMachine( 7146): entry::NETWORK_CHECK
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7146): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7146): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7146): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7146): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7146): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7146): entry::SUCCESS
D/hcjo    ( 7146): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1302): Starting #8
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
D/hcjo    ( 7146): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7146): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7146): exit::SUCCESS
D/InitializeManagerStateMachine( 7146): entry::IDLE
,I/Hs20UtilService( 1302): Starting #9
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1302): Starting #10
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1302): Starting #11
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  849): callSECApi what=220
D/WifiStateMachine(  849): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6796): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6796): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6796): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6796): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7587): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  849): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=849
,D/DisplayPowerController(  849): getFinalBrightness : 8 -> 8
D/PowerManagerService(  849): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  849): lcd : 8 +
D/DisplayPowerController(  849): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  849): lcd : 8 -
,D/DisplayPowerController(  849): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7607): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7607): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7607): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7607): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7607): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7626): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7626): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452693150434
,I/KLMS-2.4.503: ( 7626): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7626): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7626): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7626): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7626): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SO_AGENT( 7645): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5166): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SA      ( 6831): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6831): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6831): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6831): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6831): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6831): [SCU] == networkStateCheck == true
,I/SA      ( 6831): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6831): isChinaCountryCode : false
I/SA      ( 6831): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6831): [OR] == networkStateCheck true ==
,I/SA      ( 6831): [OR] GetMyCountryZoneTask
,I/SA      ( 6831): [OR] onReceive END
,I/SA      ( 6831): [SRS] prepareGetMyCountryZone
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6831): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6831): [SSP] query invoked
,I/SA      ( 6831): [TPMU] GetMccFromDB : null
I/SA      ( 6831): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6831): [TPM] isNoProxy(default) : true
,D/accuweather( 7662): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/accuweather( 7662): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7686): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7686): premStatus:2
,I/KnoxUsageLogPro( 7686): isEulaShown : false
I/KnoxUsageLogPro( 7686): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6831): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/Headlines( 5480): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5480): getCountryCode(): countryCode = DE
,D/Headlines( 5480): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5480): queryCategory.  mRequest is not initialized.
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/HeadlinesCardManager( 5480): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5480): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5480): requestUpdateNewsWelcomeCard !!! no welcome card
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7819): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7819): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7819): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,D/RCPManagerService(  849): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7505): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7505): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7505): StateMachine : Current State = 1
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7505): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5586): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): last run: 1452672209054 -- System.currentTimeMillis()-last_run: 20941566
,D/com.peel.receiver.ConnectivityActionReceiver( 5586): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5586): ... skip last_72_check
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2475): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7146): AutoUpdateManager:IDLE:execute
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/InitializeManagerStateMachine( 7146): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7146): exit::IDLE
D/InitializeManagerStateMachine( 7146): entry::NETWORK_CHECK
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7146): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7146): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7146): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7146): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7146): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7146): entry::SUCCESS
,D/hcjo    ( 7146): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7146): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7146): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7146): exit::SUCCESS
D/InitializeManagerStateMachine( 7146): entry::IDLE
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/art     ( 1772): Explicit concurrent mark sweep GC freed 29291(1786KB) AllocSpace objects, 17(1377KB) LOS objects, 40% free, 17MB/29MB, paused 467us total 37.159ms
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
,D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2475): [AccountUtils] Account not ready
W/Kids    ( 2475): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2475): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2475): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2475): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2475): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2475): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2475): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/Watchdog(  849): !@Sync 3
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/SMD     (  288): DCD ON
,I/SA      ( 6831): [RC New] Execute method=[GET] start
,I/SA      ( 6831): [RC New] Security=[true]
,I/System.out( 6831): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6831): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 6831): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager(  849): waitForAlarm result :4
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1772): Connected
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1772): Message class com.google.f.a.a.p
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6831): [RC New] [v2liruge] api execute + 674
,I/SA      ( 6831): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6831): AsyncTask #1 calls detatch()
,I/SA      ( 6831): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6831): [OCP] update openData : PL
,I/SA      ( 6831): [TPMU] getNetworkMcc : 
,I/SA      ( 6831): [SCU] saveMccToPreferece Start
,I/SA      ( 6831): [SCU] RegionMCC : 260
I/SA      ( 6831): [SSP] query invoked
,I/SA      ( 6831): [TPMU] GetMccFromDB : null
,I/SA      ( 6831): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6831): [SCU] saveMccToPreferece End
,I/SA      ( 6831): [RC New] executeRequest [v2liruge] end. 720
I/SA      ( 6831): [RC New] Execute end
I/SA      ( 6831): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6831): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  849): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  849): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PowerManagerService(  849): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 849) eventTime = 106397
,D/PowerManagerService(  849): [s] UserActivityState : 2 -> 1
D/PowerManagerService(  849): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=849 (0x0)
D/PowerManagerService(  849): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=849, ws=WorkSource{10059}) (elapsedTime=3486)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/GAV4    ( 7720): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,E/SMD     (  288): DCD ON
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/PackageManager(  849): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  849): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/Zygote  ( 7939): MountEmulatedStorage()
E/Zygote  ( 7939): v2
I/libpersona( 7939): KNOX_SDCARD checking this for 10034
,I/libpersona( 7939): KNOX_SDCARD not a persona
I/ActivityManager(  849): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7939 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/InputReader(  849): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SELinux ( 7939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux ( 7939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7939): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredServicesCache( 1462): empty dynamic service
,D/TimaKeyStoreProvider( 7939): TimaSignature is unavailable
,D/ActivityThread( 7939): Added TimaKeyStore provider
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  849): mCursor = null
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,I/FeatureConfig( 7939): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/BackupManagerService(  849): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  849): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  849): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6796): mConnectivityHandler : connected
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6796): [hasSamungAccount] - No Samsung Account
,W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/CSTORAGE( 6796): ================================================
I/CSTORAGE( 6796):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6796): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6796): [GetString-S]
E/art     ( 6796): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/ResourcesManager( 7939): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6796): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6796): [GetString-E]
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_PushUtil( 6796): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6796): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6796): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6796): [ensureRegistration] - No Samsung account
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7969): MountEmulatedStorage()
E/Zygote  ( 7969): v2
I/libpersona( 7969): KNOX_SDCARD checking this for 10035
I/libpersona( 7969): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7969 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  849): Killing 6985:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/SELinux ( 7969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7969): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7969): TimaSignature is unavailable
D/ActivityThread( 7969): Added TimaKeyStore provider
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  849): failed to open /acct/uid_10003/pid_6985/cgroup.procs: No such file or directory
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): checkState()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7990): MountEmulatedStorage()
,E/Zygote  ( 7990): v2
I/libpersona( 7990): KNOX_SDCARD checking this for 10017
I/libpersona( 7990): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7990 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 7990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7990): TimaSignature is unavailable
,D/ActivityThread( 7990): Added TimaKeyStore provider
,D/ResourcesManager( 7990): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7969): getConnectedDevices
,D/-----SIC-----( 7969): ------------------skip uv
,D/-----SIC-----( 7969): ------------------skip SPO2
D/-----SIC-----( 7969): ------------------skip TGH
,I/SecureStorage( 7990): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  342): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 7990
I/SecureStorage(  342): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7969): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7969): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7969): decode(35, 19359868, 4230)
,V/MediaPlayerService(  293): decode(30, 19359868, 4230)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
V/MediaPlayerService(  293): wait for prepare
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7969): decode(32, 19213040, 15440)
V/MediaPlayerService(  293): decode(30, 19213040, 15440)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/MediaPlayerService(  293): player type = 3
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb031a6f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/AdaptiveEventManager( 1172): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1172): M updateContainers()
D/AdaptiveEventContainerSmall( 1172): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1172): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1172): pedoEvent == null
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,I/ActivityManager(  849): Killing 7000:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/AdaptiveEventManager( 1172): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1172): M updateContainers()
D/AdaptiveEventContainerSmall( 1172): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1172): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1172): pedoEvent == null
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
E/DatabaseUtils(  849): Writing exception to parcel
E/DatabaseUtils(  849): java.lang.NullPointerException: key == null
E/DatabaseUtils(  849): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  849): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  849): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  849): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  849): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  849): 	at android.os.Binder.execTransact(Binder.java:446)
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 7, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
,I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7969): decode(34, 19257568, 9226)
V/MediaPlayerService(  293): decode(30, 19257568, 9226)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb29c78d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
,V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
,I/SecMediaClock(  293): SecMediaClock constructor
,I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/ActivityManager(  849): Killing 7007:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb29c78d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,I/UpdateIcingCorporaServi( 1696): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AudioCache(  293): notify(0xb29c78d0, 6, 0, 0)
,V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/libpersona( 8041): KNOX_SDCARD checking this for 10075
I/SecVideoCapture(  293): reset
I/libpersona( 8041): KNOX_SDCARD not a persona
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
E/Zygote  ( 8041): MountEmulatedStorage()
E/Zygote  ( 8041): v2
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7969): decode(38, 19364180, 4890)
,I/ActivityManager(  849): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8041 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/MediaPlayerService(  293): decode(30, 19364180, 4890)
I/SELinux ( 8041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,I/SELinux ( 8041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8041): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
,V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,D/TimaKeyStoreProvider( 8041): TimaSignature is unavailable
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,D/ActivityThread( 8041): Added TimaKeyStore provider
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7969): decode(39, 19290344, 17329)
V/MediaPlayerService(  293): decode(30, 19290344, 17329)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/ResourcesManager( 8041): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): addBatteryData
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7969): decode(40, 19190536, 6644)
V/MediaPlayerService(  293): decode(30, 19190536, 6644)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/FileShare-Server( 8041): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
,I/UpdateIcingCorporaServi( 1696): UpdateCorporaTask done [took 128 ms] updated apps [took 128 ms] 
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7969): decode(41, 19266876, 23389)
V/MediaPlayerService(  293): decode(30, 19266876, 23389)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
,V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
,V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare,
V/AwesomePlayer(  293): onPrepareAsyncEvent
W/libprocessgroup(  849): failed to open /acct/uid_10020/pid_7000/cgroup.procs: No such file or directory
I/SecMediaClock(  293): SecMediaClock constructor
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_7007/cgroup.procs: No such file or directory
,I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
I/ActivityManager(  849): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8072 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  849): Killing 7033:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,E/Zygote  ( 8072): MountEmulatedStorage()
E/Zygote  ( 8072): v2
I/libpersona( 8072): KNOX_SDCARD checking this for 1000
I/libpersona( 8072): KNOX_SDCARD not a persona
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 2, 0, 0)
,V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 7, 0, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb031a6f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
,I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
,I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7969): decode(36, 19156232, 8154)
,I/SELinux ( 8072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/MediaPlayerService(  293): decode(30, 19156232, 8154)
,V/MediaPlayerService(  293): player type = 3
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
,V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 8, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
,V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
,V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
,V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/TimaKeyStoreProvider( 8072): TimaSignature is unavailable
,D/ActivityThread( 8072): Added TimaKeyStore provider
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 200, 973, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 1, 0, 0)
V/AudioCache(  293): prepared
,V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,W/libprocessgroup(  849): failed to open /acct/uid_10112/pid_7033/cgroup.procs: No such file or directory
,D/ResourcesManager( 8072): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7969): decode(42, 19129712, 4804)
V/MediaPlayerService(  293): decode(30, 19129712, 4804)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
,I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
,V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 200, 973, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 1, 0, 0)
V/AudioCache(  293): prepared
,V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): addBatteryData
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7969): decode(43, 19099164, 9400)
,V/MediaPlayerService(  293): decode(30, 19099164, 9400)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
,V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb144e290, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
,V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,D/ShortcutReceiver( 8072):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,V/MediaPlayer( 7969): decode(49, 19172584, 4112)
,V/MediaPlayerService(  293): decode(35, 19172584, 4112)
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(35, 19172584, 4112)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(36) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): onPrepareAsyncEvent
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/AudioPlayer(  293): First fillBuffer call!!
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb144e290, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
,I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
,E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/MediaPlayer( 7969): decode(44, 19307764, 52024)
V/MediaPlayerService(  293): decode(30, 19307764, 52024)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OggExtractor(  293): ~MyVorbisExtractor --
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,I/OggExtractor(  293): ~OggExtractor --
V/AwesomePlayer(  293): play
,V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(48000, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
,D/PackageBroadcastService( 2475): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/PeopleContactsSync( 2475): CP2 sync disabled
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 2, 0, 0)
,V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 7, 0, 0)
V/AudioCache(  293): ignored
,V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
,V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a6f0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthServiceInstalled() : HealthService is Installed.
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/MediaPlayer( 7969): decode(45, 19172584, 4112)
V/MediaPlayerService(  293): decode(30, 19172584, 4112)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(1)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
,V/AudioCache(  293): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
I/AudioPlayer(  293): First fillBuffer call!!
V/AudioCache(  293): notify(0xb29c78d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  293): wait for playback complete
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
,V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb29c78d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb29c78d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
,I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
,V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7969): decode(46, 19235660, 21825)
V/MediaPlayerService(  293): decode(30, 19235660, 21825)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  293): reset_l()
I/ActivityManager(  849): Killing 7051:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
,V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 5, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  293): Audio channels(2)
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
,V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb0b1c100, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb0b1c100, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
,I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7969): decode(47, 19134596, 21552)
V/MediaPlayerService(  293): decode(30, 19134596, 21552)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
,V/StagefrightPlayer(  293): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
,V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
,I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,D/SSRM:m  (  849): SIOP:: AP = 410, PST = 418, CUR = 300
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
,V/MediaPlayerService(  293): wait for playback complete
,I/AudioPlayer(  293): First fillBuffer call!!
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb144e290, 8, 0, 0)
,V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
W/libprocessgroup(  849): failed to open /acct/uid_10118/pid_7051/cgroup.procs: No such file or directory
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
I/OggExtractor(  293): ~OggExtractor ++
,I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
,V/MediaPlayer( 7969): decode(48, 19228560, 7017)
V/MediaPlayerService(  293): decode(30, 19228560, 7017)
,V/MediaPlayerService(  293): player type = 3
V/AwesomePlayer(  293): setDefault
V/AwesomePlayer(  293): constructor
V/AwesomePlayer(  293): setDefault
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
V/StagefrightPlayer(  293): StagefrightPlayer
V/AwesomePlayer(  293): setListener
V/StagefrightPlayer(  293): initCheck
V/AwesomePlayer(  293): setAudioSink
V/StagefrightPlayer(  293): setDataSource(30, 19228560, 7017)
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
D/Utils   (  293): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  293): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  293): mBitrate = -1 bits/sec
I/OggExtractor(  293): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  293): current audio track index (0) is added to vector
V/AwesomePlayer(  293): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  293): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  293): prepare
,V/AwesomePlayer(  293): prepareAsync
V/MediaPlayerService(  293): wait for prepare
V/AwesomePlayer(  293): onPrepareAsyncEvent
I/SecMediaClock(  293): SecMediaClock constructor
I/SecMediaClock(  293): reset
I/SecVideoCapture(  293): SecVideoCapture constructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): initAudioDecoder
V/AwesomePlayer(  293): checkOffloadExceptions is true
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  293): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  293): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  293): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  293): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  293): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/SecureStorage(  342): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  342): [INFO]: SPID(0x00000005)PID: 7990, TID: 8002
V/AwesomePlayer(  293): finishAsyncPrepare_l
V/AwesomePlayer(  293): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 200, 973, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 5, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 1, 0, 0)
V/AudioCache(  293): prepared
V/AudioCache(  293): wait - success
V/MediaPlayerService(  293): start
V/StagefrightPlayer(  293): start
,V/AwesomePlayer(  293): play
V/AwesomePlayer(  293): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  293): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  293): start of Playback, useOffload 0
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  293): >>>UHQA initOutputFormat 16
I/OMXCodec(  293): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  293): Audio channels(2)
,I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  293): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  293): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  293): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb031a3d0, 6, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): addBatteryData
I/AudioPlayer(  293): First fillBuffer call!!
I/AudioPlayer(  293): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  293): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,V/MediaPlayerService(  293): wait for playback complete
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  293): postAudioEOS delayUs (0)
,V/AwesomePlayer(  293): onCheckAudioStatus
V/AwesomePlayer(  293): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  293): onStreamDone
V/AwesomePlayer(  293): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  293): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  293): notify(0xb031a3d0, 2, 0, 0)
V/AudioCache(  293): playback complete - thread will wake up later
V/AwesomePlayer(  293): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 7, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  293): addBatteryData
V/AudioCache(  293): wait - success
V/StagefrightPlayer(  293): reset
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  293): notify(0xb031a3d0, 8, 0, 0)
V/AudioCache(  293): ignored
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,D/AudioPlayer(  293): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  293): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  293): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  293): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  293): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  293): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  293): ~OggSource --
,I/OggExtractor(  293): ~OggExtractor ++
I/OggExtractor(  293): ~MyVorbisExtractor ++ 
I/OggExtractor(  293): ~MyVorbisExtractor --
I/OggExtractor(  293): ~OggExtractor --
,I/AudioPlayer(  293): reset out
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  293): SecVideoCapture destructor
I/SecVideoCapture(  293): reset
V/AwesomePlayer(  293): mSecCapture clear
I/SecMediaClock(  293): SecMediaClock destructor
V/AwesomePlayer(  293): mSecMediaClock clear
,V/StagefrightPlayer(  293): ~StagefrightPlayer
V/StagefrightPlayer(  293): reset
V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
,V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
V/AwesomePlayer(  293): mSecMediaClock clear
V/AwesomePlayer(  293): destructor
,V/AwesomePlayer(  293): reset_l()
V/AwesomePlayer(  293): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  293): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  293): mAudioTrackVector clear
V/AwesomePlayer(  293): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  293): mSecCapture clear
,V/AwesomePlayer(  293): mSecMediaClock clear
,I/SecureStorage( 7990): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7990): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7969): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 7969): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7969): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7969): Android Version: 5.0
D/SecSQLiteDatabase( 7969): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7969): openSecureDatabase...
,I/SecSQLiteDatabase( 7969): private openSecureDatabase...
I/SecSQLiteConnectionPool( 7969): OpenSecure
I/SecSQLiteConnectionPool( 7969): OpenSecure with password
I/SecSQLiteConnectionPool( 7969): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7969): ...private openSecureDatabase
I/SecSQLiteDatabase( 7969): ...openSecureDatabase
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/SecSQLiteOpenHelper( 7969): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7969): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7969): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7969): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7969): 	at java.lang.Integer.invalidInt(Integer.java:138)
,W/System.err( 7969): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7969): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7969): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
,W/System.err( 7969): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7969): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7969): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7969): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/jxcore-log( 7420): Test app app.js loaded
I/jxcore-log( 7420): 
,I/chromium( 7420): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7146): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7146): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7146): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7146): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7146): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7146): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7146): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7146): entry::IDLE
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7677): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7146): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7146): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7146): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 7146): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7146): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7146): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7146): entry::IDLE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/GAV3    ( 7969): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  288): DCD ON
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/FactoryTest( 6712): Not factory mode
,D/FactoryTest( 6712): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6712): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6712): still no open session command from host, so toast
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6712): Timeline: Activity_launch_request id:com.android.settings time:117271
,E/PersonaManagerService(  849): inState():  stateMachine is null !!
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  849): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  849): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  849): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 3565): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3565): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/MTPRx   ( 6712): started activity for popup
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager( 6712): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6712): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6712): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/InputMethodManagerService(  849): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  849): Invalid thumbnail dimensions: 576x576
,W/InputMethodManagerService(  849): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3da96f66 attribute=null, token = android.os.BinderProxy@24712054
,I/SQLiteSecureOpenHelper( 3565): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3565): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/AlarmManager(  849): waitForAlarm result :4
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6712): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6712): dev.kiessupport is : TRUE
,D/Activity( 6712): performCreate Call secproduct feature valuefalse
,D/Activity( 6712): performCreate Call debug elastic valuetrue
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ActivityManager(  849): post active user change for 0
D/KnoxTimeoutHandler(  849): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  849): handleActiveUserChange for user 0
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,I/Timeline( 7420): Timeline: Activity_idle id: android.os.BinderProxy@3beb0477 time:117539
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6583): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6583): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6583): [1] 5.onFinished: Scheduling replication attempt 3.
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  849): Explicit concurrent mark sweep GC freed 59569(3MB) AllocSpace objects, 8(2MB) LOS objects, 29% free, 38MB/54MB, paused 1.319ms total 107.899ms
,E/SMD     (  288): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,D/SSRM:m  (  849): SIOP:: AP = 390, PST = 411, CUR = 300
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/CustomFrequencyManagerService(  849): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  849): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  849): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/CustomFrequencyManagerService(  849): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 849  tag : ACTIVITY_RESUME_BOOSTER@10
,V/AlarmManager(  849): waitForAlarm result :4
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/SSRM:m  (  849): SIOP:: AP = 340, PST = 397, CUR = 300
,D/X       (  849): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1227):  LEVEL : -1
,I/SystemBroadcastReceiver( 7173): [#DCM#] [DCM_Performance] onReceive completed in time  998 microsec. 
,I/SystemBroadcastReceiver( 7173): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7173): [#DCM#] onReceive action = EVENT_SIOP
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  849): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8163 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,E/Zygote  ( 8163): MountEmulatedStorage()
E/Zygote  ( 8163): v2
I/libpersona( 8163): KNOX_SDCARD checking this for 10054
I/libpersona( 8163): KNOX_SDCARD not a persona
,I/SELinux ( 8163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8163): TimaSignature is unavailable
,D/ActivityThread( 8163): Added TimaKeyStore provider
,D/ResourcesManager( 8163): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8163): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8163): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8163): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8163): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8163): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 8163): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8163): core_num = 4
,W/linker  ( 8163): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8163): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8163): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 8163): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8163):  SIOP_LEVEL: -1
,I/ActivityManager(  849): Killing 7067:com.samsung.helphub/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_7067/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/PowerManagerService(  849): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  849): getFinalBrightness : 1 -> 1
D/PowerManagerService(  849): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  849): getFinalBrightness : 1 -> 1
D/lights  (  849): lcd : 1 +
,D/lights  (  849): lcd : 1 -
,D/DisplayPowerController(  849): getFinalBrightness : 1 -> 1
,E/SMD     (  288): DCD ON
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  849): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  849): !@Sync 4
,E/SMD     (  288): DCD ON
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  849): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  849): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/PowerManagerService(  849): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  849): Nap time (uid 1000)...
I/PowerManagerService(  849): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  849): Going to sleep due to screen timeout (uid 1000)...
D/InputManager-JNI(  849): setDeviceInteractive: 0
,D/PowerManagerService(  849): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  849): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  849): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService(  849): handleSandman : startDream()
,D/InputManager-JNI(  849): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  849): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  849): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  849): Sleeping (uid 1000)...
D/PowerManagerService(  849): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  849): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  849): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  849): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  849): 	.unregisterCallback : 1, client=
,D/SContextService(  849): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@21443c36, Service = Auto Rotation, used = 1
,W/CAE     (  849): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  849): stop(ContextProvider.java:149)
,V/CAE     (  849): clear(AutoRotationRunner.java:182)
V/CAE     (  849): disable(AutoRotationRunner.java:171)
,I/CAE     (  849): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  849): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  299): sendContextData: -78, 7, 0, 0
,D/CAE     (  849): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  849): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  849): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  849): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  849): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  849): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  849): removeSContextService() : service = Auto Rotation
D/SContextService(  849): ===== SContext Service List =====
D/SContextManager(  849):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@37a0e5cf, service=Auto Rotation
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3565): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3565): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/KeyguardViewMediator( 1172): timeout : 5000
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/DisplayPowerController(  849): ColorFade: onAnimationStart
,D/DisplayPowerController(  849): getFinalBrightness : 8 -> 0
,E/SMD     (  288): DCD ON
,D/lights  (  849): lcd : 0 +
,D/DisplayPowerController(  849): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1172): handleNotifyScreenOff
D/lights  (  849): lcd : 0 -
,D/LightsService(  849): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 849) 
D/LightsService(  849): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  849): [SvcLED]  onSensorChanged::light value = 2
,D/SensorManager(  849): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  849): unregisterListener ::   
D/lights  (  849): led_pattern : 5 +
,D/BatteryService(  849): turn on LED for fully charged
,D/lights  (  849): led_pattern : 5 -
,D/LightsService(  849): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
,I/CAE     (  849): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  849): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  849): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  849): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  299): sendContextData: -76, 13, -46, 0
,I/CAE     (  849): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 13, 53, 4,
,D/SensorHubManager(  849): SendSensorHubData: send data = -63, 14, 13, 53, 4
D/Sensorhubs(  299): sendContextData: -63, 14, 13, 53, 4
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  849):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  849): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  849): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  849): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  849): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  849): do suspend true
,D/NotificationService(  849): ACTION_SCREEN_OFF
D/LightsService(  849): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 849) 
D/LightsService(  849): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  849): [SvcLED]  onSensorChanged::light value = 2
,D/SensorManager(  849): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  849): unregisterListener ::   
,D/lights  (  849): led_pattern : 3 +
,D/audio_hw_primary(  293): adev_set_parameters: enter: screen_state=off
V/voice   (  293): voice_set_parameters: enter: screen_state=off
V/voice   (  293): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  293): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  293): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  293): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  293): adev_set_parameters: exit
,D/lights  (  849): led_pattern : 3 -
D/LightsService(  849): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,I/SecExternalDisplayIntents_Java(  849): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  849): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  849): Bridge Server is not available
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1172): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  849): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  849): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1462): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1172):      ACTION_SCREEN_OFF is finished!!!! 
,D/DisplayPowerState(  849): !@ ColorFade entry
,D/DisplayPowerController(  849): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  849): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  849): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  849): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  849): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  849): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,E/StatusBar( 1172): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1172): dismissHelpPopup 
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1970): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 1970): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/SensorManager(  849): unregisterListener ::   
,E/Sensors (  849): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  849): unregisterListener ::   
,D/DisplayPowerController(  849): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  849): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  849): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  849): Display changed displayId=0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ActivityManager(  849): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  849): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/SystemBroadcastReceiver( 7173): [#DCM#] [DCM_Performance] onReceive completed in time  180 microsec. 
,I/SystemBroadcastReceiver( 7173): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7173): [#DCM#] onReceive action = EVENT_SCREEN_OFF
,I/DCMController( 7173): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  849): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  849): SIOP:: AP = 330, PST = 382, CUR = 300
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
,I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  849): Excessive delay in setPowerMode(): 255ms
D/PowerManagerService(  849): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  849): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  849): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  849): Got set_interactive hint
,I/PowerManagerService(  849): [PWL] Off : 0s ago,
I/PowerManagerService(  849): [PWL]   PowerManagerService.Display: ref count=2
,I/PowerManagerService(  849): [PWL]     mDisplayReady : false
D/DisplayPowerController(  849): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  849): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  849): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,V/AlarmManager(  849): waitForAlarm result :4
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  849): stay LED for fully charged
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6583): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6583): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6583): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  849): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  849): [PWL] Off : 5s ago
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON,
,D/SSRM:m  (  849): SIOP:: AP = 320, PST = 371, CUR = 300
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  849): [PWL] Off : 15s ago
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,V/AlarmManager(  849): waitForAlarm result :4
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryService(  849): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1772): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6555): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at dsf.a(PG:807)
E/HttpOperation( 6555): 	at fhk.a(PG:1126)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 8 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 10 more
,D/SSRM:m  (  849): SIOP:: AP = 310, PST = 362, CUR = 300
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
,D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,E/HttpOperation( 6555): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at ieo.a(PG:43)
E/HttpOperation( 6555): 	at iep.a(PG:93)
E/HttpOperation( 6555): 	at fhn.a(PG:59)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/ExperimentLoader( 6555): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): 	at kfv.a(PG:65)
E/ExperimentLoader( 6555): 	at kff.u(PG:385)
E/ExperimentLoader( 6555): 	at kfb.a(PG:29)
E/ExperimentLoader( 6555): 	at kff.l(PG:132)
E/ExperimentLoader( 6555): 	at ieo.a(PG:43)
E/ExperimentLoader( 6555): 	at iep.a(PG:93)
E/ExperimentLoader( 6555): 	at fhn.a(PG:59)
E/ExperimentLoader( 6555): 	at lex.a(PG:85)
E/ExperimentLoader( 6555): 	at lex.b(PG:132)
E/ExperimentLoader( 6555): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6555): 	at fhk.a(PG:908)
E/ExperimentLoader( 6555): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6555): 	at ihi.a(PG:22)
E/ExperimentLoader( 6555): 	at kft.a(PG:91)
E/ExperimentLoader( 6555): 	at kfv.a(PG:62)
E/ExperimentLoader( 6555): 	... 12 more
E/ExperimentLoader( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6555): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6555): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6555): 	at ihi.a(PG:19)
E/ExperimentLoader( 6555): 	... 14 more
,E/SQLiteLog( 1772): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [getaccountstatus] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at ixd.a(PG:248)
E/HttpOperation( 6555): 	at ixd.b(PG:206)
E/HttpOperation( 6555): 	at ixd.a(PG:175)
E/HttpOperation( 6555): 	at fig.a(PG:78)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,E/EsSyncAdapterService( 6555): Sync failure
E/EsSyncAdapterService( 6555): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6555): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6555): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6555): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6555): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6555): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6555): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6555): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6555): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6555): 	... 10 more
E/EsSyncAdapterService( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6555): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6555): 	... 12 more
E/EsSyncAdapterService( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6555): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6555): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6555): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  849): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 156440, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  849): mCursor = null
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1772): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager(  849): waitForAlarm result :4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6583): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6583): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6583): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  849): !@Sync 5
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
,I/MotionRecognitionService(  849): setPowerConnected  = true
,D/BatteryService(  849): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  849): SIOP:: AP = 310, PST = 353, CUR = 300
,I/PowerManagerService(  849): [PWL] Off : 30s ago
,E/SMD     (  288): DCD ON
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  849): SIOP:: AP = 300, PST = 344, CUR = 300
,E/SMD     (  288): DCD ON
,V/AlarmManager(  849): waitForAlarm result :4
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  849): stay LED for fully charged
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1772): Vacuum at: now=1452693226765 tag=VacuumService
,I/GoogleURLConnFactory( 1772): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
,D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
E/Uploader( 1772): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1772): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1772): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1772): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1772): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1772): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1772): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1772): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1772): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1772): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1772): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1772): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1772): (HTTPLog)-Thread-216-225073831: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1772): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/qtaguid ( 1772): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012
V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6583): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6583): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6583): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1772): No account for auth token provided
,I/qtaguid ( 1772): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012
,W/Uploader( 1772): No account for auth token provided
,I/qtaguid ( 1772): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012
,W/Uploader( 1772): No account for auth token provided
,I/qtaguid ( 1772): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012
,W/Uploader( 1772): No account for auth token provided
,I/qtaguid ( 1772): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012,
,W/Uploader( 1772): No account for auth token provided
,I/qtaguid ( 1772): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012
,W/Uploader( 1772):  no longer exists, so no auth token.
,I/qtaguid ( 1772): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1772, getuid(): 10012
,E/SQLiteLog( 1772): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  849): waitForAlarm result :4
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7345): Starting books sync, d
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1772): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7345): null auth token
,I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/qtaguid ( 7345): Untagging socket 34
,I/PowerManagerService(  849): [PWL] Off : 50s ago
,I/PowerManagerService(  849): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  849): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  849): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=849, ws=WorkSource{10082}) (elapsedTime=409)
,W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
,W/ApiaryClient( 7345): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4037348117199637571&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  849): SIOP:: AP = 300, PST = 339, CUR = 300
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7345): null auth token
,I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/qtaguid ( 7345): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/qtaguid ( 7345): Untagging socket 34
,W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
,W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
,W/ApiaryClient( 7345): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4037348117199637571&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
,I/MotionRecognitionService(  849): setPowerConnected  = true
,D/BatteryService(  849): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7345): null auth token
,I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/qtaguid ( 7345): Untagging socket 34
,W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
,W/ApiaryClient( 7345): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4037348117199637571&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/BooksSync( 7345): Soft error
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4037348117199637571&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7345): Headers suppressed
E/BooksSync( 7345): 
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7345): Sync error
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=4037348117199637571&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7345): Headers suppressed
E/BooksSync( 7345): 
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7345): Finished books sync
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  849): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158435, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  849): Explicit concurrent mark sweep GC freed 65137(3MB) AllocSpace objects, 34(999KB) LOS objects, 29% free, 38MB/54MB, paused 7.286ms total 191.487ms
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  849): mCursor = null
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at dsf.a(PG:807)
E/HttpOperation( 6555): 	at fhk.a(PG:1126)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 8 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 10 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/art     ( 1772): Explicit concurrent mark sweep GC freed 50124(2MB) AllocSpace objects, 81(5MB) LOS objects, 40% free, 18MB/30MB, paused 2.376ms total 134.211ms
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1772): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at ieo.a(PG:43)
E/HttpOperation( 6555): 	at iep.a(PG:93)
E/HttpOperation( 6555): 	at fhn.a(PG:59)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,E/ExperimentLoader( 6555): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): 	at kfv.a(PG:65)
E/ExperimentLoader( 6555): 	at kff.u(PG:385)
E/ExperimentLoader( 6555): 	at kfb.a(PG:29)
E/ExperimentLoader( 6555): 	at kff.l(PG:132)
E/ExperimentLoader( 6555): 	at ieo.a(PG:43)
E/ExperimentLoader( 6555): 	at iep.a(PG:93)
E/ExperimentLoader( 6555): 	at fhn.a(PG:59)
E/ExperimentLoader( 6555): 	at lex.a(PG:85)
E/ExperimentLoader( 6555): 	at lex.b(PG:132)
E/ExperimentLoader( 6555): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6555): 	at fhk.a(PG:908)
E/ExperimentLoader( 6555): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6555): 	at ihi.a(PG:22)
E/ExperimentLoader( 6555): 	at kft.a(PG:91)
E/ExperimentLoader( 6555): 	at kfv.a(PG:62)
E/ExperimentLoader( 6555): 	... 12 more
E/ExperimentLoader( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6555): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6555): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6555): 	at ihi.a(PG:19)
E/ExperimentLoader( 6555): 	... 14 more
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
,D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6555): [getaccountstatus] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at ixd.a(PG:248)
E/HttpOperation( 6555): 	at ixd.b(PG:206)
E/HttpOperation( 6555): 	at ixd.a(PG:175)
E/HttpOperation( 6555): 	at fig.a(PG:78)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,E/EsSyncAdapterService( 6555): Sync failure
E/EsSyncAdapterService( 6555): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6555): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6555): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6555): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6555): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6555): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6555): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6555): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6555): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6555): 	... 10 more
E/EsSyncAdapterService( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6555): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6555): 	... 12 more
E/EsSyncAdapterService( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6555): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6555): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6555): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PanelView( 1172): There is/are notification(s) 
,D/SyncManager(  849): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 189762, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  849): mCursor = null
,E/SQLiteLog( 1772): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  849): waitForAlarm result :8
,E/Watchdog(  849): !@Sync 6
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  849): SIOP:: AP = 300, PST = 331, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  849): SIOP:: AP = 300, PST = 320, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  849): [PWL] Off : 75s ago
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,V/AlarmManager(  849): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  849): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/Watchdog(  849): !@Sync 7
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 306, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 302, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  849): [PWL] Off : 105s ago
,E/SMD     (  288): DCD ON
,V/AlarmManager(  849): waitForAlarm result :4
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7345): Starting books sync, d
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1772): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7345): null auth token
,I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/qtaguid ( 7345): Untagging socket 34
,W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
,W/ApiaryClient( 7345): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5902585211840028898&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7345): null auth token
,I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/qtaguid ( 7345): Untagging socket 34
,W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
,W/ApiaryClient( 7345): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5902585211840028898&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1772): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1772): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1772): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1772): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1772): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7345): Authentication error
E/BooksAccountManager( 7345): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7345): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7345): null auth token
,I/qtaguid ( 7345): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7345, getuid(): 10082
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/qtaguid ( 7345): Untagging socket 34
,W/ApiaryClient( 7345): Error response from books API: {
W/ApiaryClient( 7345):  "error": {
W/ApiaryClient( 7345):   "errors": [
W/ApiaryClient( 7345):    {
W/ApiaryClient( 7345):     "domain": "global",
W/ApiaryClient( 7345):     "reason": "required",
W/ApiaryClient( 7345):     "message": "Login Required",
W/ApiaryClient( 7345):     "locationType": "header",
W/ApiaryClient( 7345):     "location": "Authorization"
W/ApiaryClient( 7345):    }
W/ApiaryClient( 7345):   ],
W/ApiaryClient( 7345):   "code": 401,
W/ApiaryClient( 7345):   "message": "Login Required"
W/ApiaryClient( 7345):  }
W/ApiaryClient( 7345): }
,W/ApiaryClient( 7345): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5902585211840028898&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7345): Headers suppressed
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/BooksSync( 7345): Soft error
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5902585211840028898&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7345): Headers suppressed
E/BooksSync( 7345): 
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7345): Sync error
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7345): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5902585211840028898&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7345): Headers suppressed
E/BooksSync( 7345): 
E/BooksSync( 7345): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7345): Finished books sync
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  849): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 221218, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  849): mCursor = null
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager(  849): waitForAlarm result :8
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  849): !@Sync 8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
,I/MotionRecognitionService(  849): setPowerConnected  = true
,D/BatteryService(  849): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 295, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,V/AlarmManager(  849): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,I/PowerManagerService(  849): [PWL] Off : 140s ago
,I/PowerManagerService(  849): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  849): [PWL]     mWakeLockSummary : 0x1
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  849): stay LED for fully charged
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
,I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6555): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at dsf.a(PG:807)
E/HttpOperation( 6555): 	at fhk.a(PG:1126)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 8 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 10 more
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  849): uri = 14 selection = getSealedState
D/SecContentProvider2(  849): mCursor = null
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6555): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at kff.l(PG:132)
E/HttpOperation( 6555): 	at ieo.a(PG:43)
E/HttpOperation( 6555): 	at iep.a(PG:93)
E/HttpOperation( 6555): 	at fhn.a(PG:59)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,E/ExperimentLoader( 6555): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6555): 	at kfv.a(PG:65)
E/ExperimentLoader( 6555): 	at kff.u(PG:385)
E/ExperimentLoader( 6555): 	at kfb.a(PG:29)
E/ExperimentLoader( 6555): 	at kff.l(PG:132)
E/ExperimentLoader( 6555): 	at ieo.a(PG:43)
E/ExperimentLoader( 6555): 	at iep.a(PG:93)
E/ExperimentLoader( 6555): 	at fhn.a(PG:59)
E/ExperimentLoader( 6555): 	at lex.a(PG:85)
E/ExperimentLoader( 6555): 	at lex.b(PG:132)
E/ExperimentLoader( 6555): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6555): 	at fhk.a(PG:908)
E/ExperimentLoader( 6555): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6555): 	at ihi.a(PG:22)
E/ExperimentLoader( 6555): 	at kft.a(PG:91)
E/ExperimentLoader( 6555): 	at kfv.a(PG:62)
E/ExperimentLoader( 6555): 	... 12 more
E/ExperimentLoader( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6555): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6555): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6555): 	at ihi.a(PG:19)
E/ExperimentLoader( 6555): 	... 14 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1772): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1772): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1772): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1772): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1772): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 294, CUR = 300
,V/BitmapFactory( 1772): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  849): uri = 14 selection = getSealedState
,D/SecContentProvider2(  849): mCursor = null
E/SMD     (  288): DCD ON
D/SecContentProvider2(  849): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  849): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6555): [getaccountstatus] Unexpected exception
E/HttpOperation( 6555): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6555): 	at kfv.a(PG:65)
E/HttpOperation( 6555): 	at kff.u(PG:385)
E/HttpOperation( 6555): 	at kfb.a(PG:29)
E/HttpOperation( 6555): 	at ixd.a(PG:248)
E/HttpOperation( 6555): 	at ixd.b(PG:206)
E/HttpOperation( 6555): 	at ixd.a(PG:175)
E/HttpOperation( 6555): 	at fig.a(PG:78)
E/HttpOperation( 6555): 	at lex.a(PG:85)
E/HttpOperation( 6555): 	at lex.b(PG:132)
E/HttpOperation( 6555): 	at fhk.a(PG:1146)
E/HttpOperation( 6555): 	at fhk.a(PG:908)
E/HttpOperation( 6555): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6555): 	at ihi.a(PG:22)
E/HttpOperation( 6555): 	at kft.a(PG:91)
E/HttpOperation( 6555): 	at kfv.a(PG:62)
E/HttpOperation( 6555): 	... 12 more
E/HttpOperation( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6555): 	at gde.c(Unknown Source)
E/HttpOperation( 6555): 	at gde.b(Unknown Source)
E/HttpOperation( 6555): 	at ihi.a(PG:19)
E/HttpOperation( 6555): 	... 14 more
,E/EsSyncAdapterService( 6555): Sync failure
E/EsSyncAdapterService( 6555): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6555): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6555): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6555): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6555): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6555): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6555): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6555): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6555): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6555): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6555): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6555): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6555): 	... 10 more
E/EsSyncAdapterService( 6555): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6555): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6555): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6555): 	... 12 more
E/EsSyncAdapterService( 6555): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6555): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6555): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6555): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6555): 	... 14 more
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/SyncManager(  849): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 256318, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2850): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  849): mCursor = null
,E/SQLiteLog( 1772): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD ON
,E/Watchdog(  849): !@Sync 9
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
,I/MotionRecognitionService(  849): setPowerConnected  = true
,D/BatteryService(  849): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  288): DCD ON
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 292, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  849): waitForAlarm result :4
,D/ConnectivityService(  849): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  849): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  849): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  849): stay LED for fully charged
D/BatteryService(  849): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  849):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  849): Plugged
I/MotionRecognitionService(  849): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3236): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3236): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  849): SIOP:: AP = 290, PST = 291, CUR = 300
,I/jxcore-log( 7420): --= Surplus to requirements =--
I/jxcore-log( 7420): 
,I/jxcore-log( 7420): ****TEST TOOK:  ms ****
I/jxcore-log( 7420): 
I/jxcore-log( 7420): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7420): 
,E/SMD     (  288): DCD ON
,D/AndroidRuntime( 8408): 
D/AndroidRuntime( 8408): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8408): CheckJNI is OFF
,D/AndroidRuntime( 8408): setted country_code = Germany
,D/AndroidRuntime( 8408): setted countryiso_code = DE
,D/AndroidRuntime( 8408): setted sales_code = DBT
,D/AndroidRuntime( 8408): readGMSProperty: start
D/AndroidRuntime( 8408): readGMSProperty: already setted!!
,D/AndroidRuntime( 8408): readGMSProperty: end
,D/AndroidRuntime( 8408): addProductProperty: start
,D/TimaService(  849): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  849): TimaServiceHandler.handleMessage what =1
,D/TimaService(  849): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  849): initializing...
I/TLC_TIMA_PKM_initialize(  849): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize(  849): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  849): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  849): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  849): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  849): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  849): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  849): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: (  849): App is not loaded in QSEE
,D/QSEECOMAPI: (  849): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  849): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  849): Trustlet response is completed
,E/AffinityControl( 8408): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8408): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  849): START PACKAGE DELETE: observer{914979949}
D/PackageManager(  849): pkg{<packageName>}
D/PackageManager(  849): user{0}
D/PackageManager(  849): caller{2000}
D/PackageManager(  849): flags{3}
D/PersonaManagerService(  849): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  849): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  849): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  849): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  849): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  849): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  849): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  849): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  849): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  849): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  849): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  849): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
,I/ActivityManager(  849): Killing 7420:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  849):   Force finishing activity ActivityRecord{8be4056 u0 com.test.thalitest/.MainActivity t18}
,D/FocusedStackFrame(  849): Set to : 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/WifiService(  849): Client connection lost with reason: 4
,I/ActivityManager(  849): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,D/ConnectivityService(  849): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 1696): Explicit concurrent mark sweep GC freed 60105(3MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 449us total 66.535ms
,I/InputReader(  849): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 4586): Explicit concurrent mark sweep GC freed 5023(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 5.408ms total 64.390ms
,W/GeofencerStateMachine( 2059): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1761): mOCRHelper is null
,D/ResourcesManager( 2850): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/KLMS-2.4.503: ( 7626): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7626): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452693358861
,I/KLMS-2.4.503: ( 7626): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7626): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  849): Explicit concurrent mark sweep GC freed 55212(3MB) AllocSpace objects, 53(1433KB) LOS objects, 29% free, 38MB/54MB, paused 1.565ms total 178.487ms
,I/art     (  849): WaitForGcToComplete blocked for 147.781ms for cause Explicit
,D/ResourcesManager(  849): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 2850): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  849): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  849): mCursor = null
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/RegisteredServicesCache( 1462): empty dynamic service
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,E/Zygote  ( 8440): MountEmulatedStorage()
E/Zygote  ( 8440): v2
I/libpersona( 8440): KNOX_SDCARD checking this for 10104
I/libpersona( 8440): KNOX_SDCARD not a persona
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
I/ActivityManager(  849): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8440 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/EnterpriseDeviceManagerService(  849): Package has changed for user 0
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Books/Books.apk
,D/EnterpriseDeviceManagerService(  849): Admin package name: com.google.android.gms
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/SELinux ( 8440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/SELinux ( 8440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider( 8440): TimaSignature is unavailable
,D/ActivityThread( 8440): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService(  849): PackageReceiver onReceive()
I/HarmonyEASService(  849): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  849): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  849): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  849): Receieved: android.intent.action.PACKAGE_REMOVED
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/SurfaceWidgetView( 1487): destroyHardwareResources():682660350
,V/EnterpriseBillingPolicy(  849): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  849): uID is 10200
V/EnterpriseBillingPolicy(  849): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  849): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  849): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  849): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  849): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  849): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  849): getBillingProfileForVpnEngine - end - null
,V/WindowOrientationListener(  849): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  849): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  849): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  849): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
D/TaskPersister(  849): removeObsoleteFile: deleting file=18_task.xml
V/WindowOrientationListener(  849): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/TaskPersister(  849): removeObsoleteFile: deleting file=18_task_thumbnail.png
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/Launcher( 1487): onRestart, Launcher: 601620894
,D/Launcher( 1487): onStart, Launcher: 601620894
D/Launcher.HomeView( 1487): onStart
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/art     (  849): Explicit concurrent mark sweep GC freed 13490(631KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 38MB/54MB, paused 5.748ms total 220.836ms
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1970): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1970): [237392/6] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBarManagerService(  849): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBarManagerService(  849): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/elm:14451( 8440): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8440): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8440): MDMBridge.setEnterpriseBridge()
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/elm:14451( 8440): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/InputMethodManagerService(  849): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  849): Got RemoteException sending setActive(false) notification to pid 7420 uid 10200
W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:14451( 8440): ElmAgentService : onCreate()
,D/elm:14451( 8440): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14451( 8440): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8440): MDMBridge.getInstance()
,D/elm:14451( 8440): MDMBridge.getAllLicenseInfoFromSDK()
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7990): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7990): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7990): onReceive() : package name is not s health. Return !!!
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/PCWCLIENTTRACE_PushUtil( 6796): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6796): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6796): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6796): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/elm:14451( 8440): MDMBridge.getAllLicenseInfoFromSDK()
,D/PackageManager(  849): delete codoeFile: 
,D/elm:14451( 8440): ElmAgentService : onDestroy().
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/PackageManager(  849): result of delete: 1{914979949}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  849): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/AndroidRuntime( 8408): Shutting down VM
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/Zygote  ( 8462): MountEmulatedStorage()
E/Zygote  ( 8462): v2
I/libpersona( 8462): KNOX_SDCARD checking this for 10038
I/libpersona( 8462): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8462 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ActivityManager(  849): Killing 7110:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  849): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  849): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/SELinux ( 8462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ResourcesManager(  849): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SELinux ( 8462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8462): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline(  849): Timeline: Activity_windows_visible id: ActivityRecord{34e51065 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:311859
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/TimaKeyStoreProvider( 8462): TimaSignature is unavailable
,D/ActivityThread( 8462): Added TimaKeyStore provider
,W/libprocessgroup(  849): failed to open /acct/uid_10166/pid_7110/cgroup.procs: No such file or directory
,D/ResourcesManager(  849): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager( 8462): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  849): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  849): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  849): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/UsbSettingsManager(  849): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  849): onPackageRemoved : com.test.thalitest
,W/ResourcesManager( 7939): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/SPPClientService( 8462): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8462): [PushClientApplication] Push log off : This is Ship build version
,W/ResourcesManager( 7939): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/SPPClientService( 8462): PushLog.txt file is not deleted.
D/SPPClientService( 8462): PushLog.txt file is not deleted.
,D/SPPClientService( 8462): ============PushLog. stop!
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 8478): MountEmulatedStorage()
E/Zygote  ( 8478): v2
I/libpersona( 8478): KNOX_SDCARD checking this for 10042
I/libpersona( 8478): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8478 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 6624:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8478): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/libprocessgroup(  849): failed to open /acct/uid_10012/pid_6624/cgroup.procs: No such file or directory
,W/ResourcesManager( 7939): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 8478): TimaSignature is unavailable
,D/ActivityThread( 8478): Added TimaKeyStore provider
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8478): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8478): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8478): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7939): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7939): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7939): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7939): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/FileUtils( 8478): Failed to chmod(/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 8478): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 8478): (3850) statement aborts at 68: [UPDATE DEVICES SET network_mode='OFF', device_priority=((16777215 & device_priority) | 67108864) WHERE transport_type='SLINK';] disk I/O error
,D/AndroidRuntime( 8478): Shutting down VM
,E/AndroidRuntime( 8478): FATAL EXCEPTION: main
E/AndroidRuntime( 8478): Process: com.samsung.android.sdk.samsunglink, PID: 8478
E/AndroidRuntime( 8478): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 8478): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8478): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8478): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8478): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8478): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8478): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8478): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8478): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8478): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8478): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8478): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8478): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 8478): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 8478): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 8478): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 8478): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 8478): 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1797)
E/AndroidRuntime( 8478): 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1726)
E/AndroidRuntime( 8478): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:464)
E/AndroidRuntime( 8478): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8478): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8478): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8478): 	... 11 more
,V/ApplicationPolicy(  849): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
I/Process ( 8478): Sending signal. PID: 8478 SIG: 9
I/SA      ( 6831): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 6831): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager(  849): Killing 7126:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
E/DropBoxManagerService(  849): Can't write: system_app_crash
E/DropBoxManagerService(  849): java.io.FileNotFoundException: /data/system/dropbox/drop185.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  849): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  849): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  849): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  849): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  849): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  849): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:14540)
E/DropBoxManagerService(  849): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  849): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  849): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  849): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  849): 	... 5 more
E/lowmemorykiller(  246): Error writing /proc/8478/oom_score_adj; errno=22
,E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  849): checkUser: useridlist=null, currentuser=0
,E/SharedPreferencesImpl( 5999): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/Zygote  ( 8499): MountEmulatedStorage()
E/Zygote  ( 8499): v2
I/libpersona( 8499): KNOX_SDCARD checking this for 10050
I/libpersona( 8499): KNOX_SDCARD not a persona
,I/ActivityManager(  849): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8499 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager(  849): Process com.samsung.android.sdk.samsunglink (pid 8478)(adj 11) has died(196,518)
,I/art     (  316): Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 11.870ms
,I/SELinux ( 8499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8499): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 8.224ms
,W/libprocessgroup(  849): failed to open /acct/uid_10170/pid_7126/cgroup.procs: No such file or directory
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 266us total 14.861ms
,W/ContextImpl(  849): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 8499): TimaSignature is unavailable
,D/ActivityThread( 8499): Added TimaKeyStore provider
I/EventHub(  849): Removing device '/dev/input/event4' due to inotify event
,D/ResourcesManager( 8499): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8499): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8499): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8499): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8499): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8499): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ContextImpl( 8499): Unable to create files subdir /data/data/com.android.mms/cache
E/ActivityThread( 8499): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  849): Removing device '/dev/input/event5' due to inotify event
,D/AndroidRuntime( 8499): Shutting down VM
,F/libc    ( 8499): Fatal signal 7 (SIGBUS), code 2, fault addr 0x747306ca in tid 8499 (com.android.mms)
,E/audit_log( 2010): File locking failed. error= Bad file number
,F/libc    ( 8499): Failed while talking to debuggerd: Broken pipe
,E/audit_log( 2010): File locking failed. error= Bad file number
,I/ActivityManager(  849): Process com.android.mms (pid 8499)(adj 0) has died(195,518)
,F/libc    ( 1302): Fatal signal 7 (SIGBUS), code 2, fault addr 0x785be29d in tid 1302 (ndroid.settings)
,F/libc    ( 1302): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2010): File locking failed. error= Bad file number
,D/WifiService(  849): Client connection lost with reason: 4
,I/ActivityManager(  849): Process com.android.settings (pid 1302)(adj 0) has died(203,518)
I/Zygote  (  316): Process 8499 exited due to signal (7)
,F/libc    (  849): Fatal signal 7 (SIGBUS), code 2, fault addr 0x722653f4 in tid 1555 (Binder_C)
F/libc    (  849): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2010): File locking failed. error= Bad file number
,I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'rcp' died
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died
I/ServiceManager(  247): service 'country_detector' died
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
W/Sensors ( 1455): sensorservice died [0xaf0beb80]
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'netstats' died
W/Sensors ( 2059): sensorservice died [0xaf0c0ec0]
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'jobscheduler' died
I/ServiceManager(  247): service 'backup' die,d
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
I/ServiceManager(  247): service 'commontime_management' died
I/ServiceManager(  247): service 'wifi' died
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
W/Sensors ( 1172): sensorservice died [0xaf0d2080]
W/AudioFlinger(  293): power manager service died !!!
W/AudioFlinger(  293): power manager service died !!!
W/Sensors ( 5999): sensorservice died [0xaf0fc480]
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (4/8)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/6)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (2/4)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/4)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=19 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (1/3)
I/SurfaceFlinger(  249): id=19 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/3)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (0/2)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/2)
I/SurfaceFlinger(  249): id=18 Removed ColorFade (1/1)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (0/0)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/0)
I/SurfaceFlinger(  249): id=18 Removed ColorFade (-2/0)
W/Sensors ( 1468): sensorservice died [0xaf064340]
W/Sensors ( 1487): sensorservice died [0xaf0c1380]
E/WifiManager( 2059): Channel connection lost
E/WifiManager( 1172): Channel connection lost
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
E/WifiManager( 1696): Channel connection lost
E/WifiManager( 1468): Channel connection lost
W/Sensors ( 2084): sensorservice died [0xaf0bebc0]
E/WifiManager( 5586): Channel connection lost
F/libc    ( 4586): Fatal signal 7 (SIGBUS), code 2, fault addr 0x747937b0 in tid 4630 (AppProvider)
F/libc    ( 4586): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2010): File locking failed. error= Bad file number
,I/Zygote  (  316): Process 1302 exited due to signal (7)
I/Zygote  (  316): Process 4586 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,E/qdhwcomposer(  249): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  249): eventControl(0, 1) failed Operation not permitted
,E/installd(  296): eof
E/installd(  296): failed to read size
I/installd(  296): closing connection
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
