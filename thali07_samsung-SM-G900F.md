#### Test 5065027865f659b_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1167): Icon Only
W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
E/HttpHelper( 7325): null auth token
I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
I/qtaguid ( 7325): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
I/qtaguid ( 7325): Untagging socket 34
W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
W/ApiaryClient( 7325): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5328944010073036184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
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
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
E/SMD     (  281): DCD ON
E/AffinityControl( 7379): AffinityControl: registerfunction enter
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
D/AndroidRuntime( 7379): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  814): inState():  stateMachine is null !!
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  814): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  814): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  814): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  814): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/AndroidRuntime( 7379): Shutting down VM
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3767): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3767): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3767): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3767): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3767): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  814): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 814) 
D/LightsService(  814): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  814): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  814): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
I/PhoneStatusBar( 1167): Icon Only
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/PanelView( 1167): There is/are notification(s) 
D/WindowManager(  814): showStatusBarByNotification() mOpenByNotification=false
D/PanelView( 1167): There is/are notification(s) 
I/DBG_DM  ( 3767): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
V/BitmapFactory( 1167): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3767): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7401): MountEmulatedStorage()
E/Zygote  ( 7401): v2
I/libpersona( 7401): KNOX_SDCARD checking this for 10367
I/libpersona( 7401): KNOX_SDCARD not a persona
V/BitmapFactory( 1167): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/ActivityManager(  814): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7401 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/KnoxNotification( 1167): ----- inflateViews : modified publicViewLocal -----
E/SELinux ( 7401): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 1167): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1167): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1167): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@285b83b4
D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1167): Icon Only
D/TimaKeyStoreProvider( 7401): TimaSignature is unavailable
D/ActivityThread( 7401): Added TimaKeyStore provider
V/ActivityManager(  814): Display changed displayId=0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBarManagerService(  814): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
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
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ConnectivityService(  814): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
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
D/ResourcesManager( 7401): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
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
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/WebViewFactory( 7401): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7401): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/LibraryLoader( 7401): Loading: webviewchromium
I/LibraryLoader( 7401): Time to load native libraries: 2 ms (timestamps 5286-5288)
I/LibraryLoader( 7401): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
V/WebViewChromiumFactoryProvider( 7401): Binding Chromium to main looper Looper (main, tid 1) {3b936b81}
I/LibraryLoader( 7401): Expected native library version number "",actual native library version number ""
I/chromium( 7401): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/BrowserStartupController( 7401): Initializing chromium process, renderers=0
W/art     ( 7401): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7401): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7401): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7401): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/Adreno-EGL( 7401): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7401): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7401): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7401): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7401): Remote Branch: 
I/Adreno-EGL( 7401): Local Patches: 
I/Adreno-EGL( 7401): Reconstruct Branch: 
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/chromium( 7401): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/chromium( 7401): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7401): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7401): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SystemWebViewEngine( 7401): CordovaWebView is running on device made by: samsung
V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/art     ( 7401): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7401): Attempt to remove local handle scope entry from IRT, ignoring
I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7325): null auth token
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/Activity( 7401): performCreate Call secproduct feature valuefalse
D/Activity( 7401): performCreate Call debug elastic valuetrue
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/qtaguid ( 7325): Untagging socket 34
W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/ApiaryClient( 7325): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5328944010073036184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/OpenGLRenderer( 7401): Render dirty regions requested: true
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ActivityManager(  814): post active user change for 0
D/KnoxTimeoutHandler(  814): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  814): handleActiveUserChange for user 0
I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
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
I/OpenGLRenderer( 7401): Initialized EGL, version 1.4
I/OpenGLRenderer( 7401): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7401): Enabling debug mode 0
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  814): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/InputMethodManagerService(  814): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
E/Adreno-ES20( 7401): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7401): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/ActivityManager(  814): Displayed com.test.thalitest/.MainActivity: +680ms
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
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/art     (  814): Explicit concurrent mark sweep GC freed 46697(2MB) AllocSpace objects, 14(1894KB) LOS objects, 29% free, 37MB/53MB, paused 1.288ms total 103.218ms
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/Timeline( 7401): Timeline: Activity_idle id: android.os.BinderProxy@ac68e98 time:95820
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/JsMessageQueue( 7401): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/CustomFrequencyManagerService(  814): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  814): mDVFSHelper.release()
D/CustomFrequencyManagerService(  814): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline(  814): Timeline: Activity_windows_visible id: ActivityRecord{a471f1b u0 com.test.thalitest/.MainActivity t12} time:95897
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
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/chromium( 7401): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7401): 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/jxcore_app_log( 7401): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358531584
,D/JX-Cordova( 7401): jxcore cordova android initializing
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  814): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/BooksSync( 7325): Soft error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5328944010073036184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7325): Sync error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5328944010073036184&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7325): Finished books sync
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  814): Killing 5339:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 67727, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  814): failed to open /acct/uid_10126/pid_5339/cgroup.procs: No such file or directory
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  814): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1167 (0x0)
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7401): Initializing JXcore engine
,W/jxcore-log( 7401): JXcore engine is ready
,W/jxcore-log( 7401): Starting JXcore engine
,E/auditd  ( 2134): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  814): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  814): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7480): MountEmulatedStorage()
E/Zygote  ( 7480): v2
I/libpersona( 7480): KNOX_SDCARD checking this for 1000
I/libpersona( 7480): KNOX_SDCARD not a persona
,I/ActivityManager(  814): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7480 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 8767(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 272us total 10.838ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 7.676ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.824ms
,I/SELinux ( 7480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7480): TimaSignature is unavailable
,D/ActivityThread( 7480): Added TimaKeyStore provider
,D/ResourcesManager( 7480): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7401): Platform android
W/jxcore-log( 7401): 
,W/jxcore-log( 7401): Process ARCH arm
W/jxcore-log( 7401): 
,D/SecurityLogAgent( 7480):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7480):  SeDenialReceiver : File path = null
,I/ActivityManager(  814): Killing 6285:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,I/GAV2    ( 7325): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  281): DCD ON
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  814): failed to open /acct/uid_10117/pid_6285/cgroup.procs: No such file or directory
,V/AlarmManager(  814): waitForAlarm result :4
,D/SSRM:m  (  814): SIOP:: AP = 390, PST = 436, CUR = 300
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6678): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6678): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6678): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/jxcore-log( 7401): JXcore Cordova bridge is ready!
I/jxcore-log( 7401): 
,W/jxcore-log( 7401): JXcore engine is started
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/jxcore  ( 7401): Error!: missing ) after argument list
E/jxcore  ( 7401): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 7401): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame(  814): Set to : 0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
W/PluginManager( 7401): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
,I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/CustomFrequencyManagerService(  814): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  814): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/SurfaceWidgetView( 1490): destroyHardwareResources():583030829
,V/WindowOrientationListener(  814): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  814): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  814): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  814): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  814): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/Launcher( 1490): onRestart, Launcher: 65504259
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/Launcher( 1490): onStart, Launcher: 65504259
D/Launcher.HomeView( 1490): onStart
,D/Launcher( 1490): onResume, Launcher: 65504259
,D/SettingsProvider(  814): name = kids_home_mode
D/SettingsProvider(  814): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  814): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  814): selectionArgs: false
D/SettingsProvider(  814): selectionArgs: 10008
D/SecContentProvider(  814): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  814): ret = -1
D/Launcher.HomeView( 1490): onResume
,D/ConnectivityService(  814): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2275): [237392/6] Surface widget resume on instance = 1
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/accuweather( 2275): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
,D/daemonapp( 1315): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/Launcher( 1490): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/chromium( 7401): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/MenuAppsGridFragment( 1490): onResume
D/daemonapp( 1315): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/WallpaperManager( 1490): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/GalleryCacheReady( 6008): Receive : home resume
,D/accuweather( 2275): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
D/accuweather( 2275): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
D/WallpaperManager( 1490): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 2275): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
,D/WallpaperManager( 1490): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/accuweather( 2275): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
,D/accuweather( 2275): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
,D/accuweather( 2275): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
,D/Mms/UIEventReceiver( 6853): ui event
,D/daemonapp( 1315): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2275): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2275): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,E/Zygote  ( 7512): MountEmulatedStorage()
E/Zygote  ( 7512): v2
I/libpersona( 7512): KNOX_SDCARD checking this for 10071
I/libpersona( 7512): KNOX_SDCARD not a persona
D/LockPatternUtilsCache( 1167): value : false
,I/ActivityManager(  814): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=7512 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,D/ActivityManager(  814): handle home activity for 0
,I/WallpaperManagerService(  814): switchPersonaWallpaper is called for personaId-0
D/ActivityManager(  814): post active user change for 0
D/WallpaperManagerService(  814):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  814): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  814): handleActiveUserChange for user 0
,I/SELinux ( 7512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/BroadcastQueue(  814): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1490, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
I/SELinux ( 7512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
E/SELinux ( 7512): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/StatusBarManagerService(  814): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,E/Zygote  ( 7521): MountEmulatedStorage()
,E/Zygote  ( 7521): v2
I/libpersona( 7521): KNOX_SDCARD checking this for 10094
I/libpersona( 7521): KNOX_SDCARD not a persona
,I/ActivityManager(  814): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7521 uid=10094 gids={50094, 9997} abi=armeabi-v7a
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,I/SELinux ( 7521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7521): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/TimaKeyStoreProvider( 7512): TimaSignature is unavailable
,D/ActivityThread( 7512): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ResourcesManager( 7512): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/Launcher( 1490): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,W/ResourcesManager( 7512): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7512): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/InputMethodManagerService(  814): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ResourcesManager( 7512): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7401): showStatusIcon on inactive InputConnection
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7521): TimaSignature is unavailable
,D/ActivityThread( 7521): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/HotwordRecognitionRnr( 1552): Starting hotword detection.
,I/MicrophoneInputStream( 1552): mic_starting gfk@1e84d306
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/AudioPolicyManager(  287): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
,D/comsamsunglog( 7512): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7512): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7512): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7512): [KK AccuPhone]>>> ==============================================================================================
V/AudioPolicyManager(  287): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  287): adev_open_input_stream: enter
E/audio_hw_primary(  287): adev_open_input_stream : jack_config 0
I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  814): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/audio_hw_primary(  287): can not make /data/snd/hal_input.pcm 
,E/audio_hw_primary(  287): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  287): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  287): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  287): adev_open_input_stream: exit
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/AudioFlinger(  287): AudioFlinger's thread 0xb1476000 ready to run
V/audio_hw_primary(  287): in_standby: enter
V/audio_hw_primary(  287): in_standby: exit:  status(0)
,V/audio_hw_primary(  287): in_standby: enter
V/audio_hw_primary(  287): in_standby: exit:  status(0)
I/Timeline( 1490): Timeline: Activity_idle id: android.os.BinderProxy@12adcba7 time:98702
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/comsamsunglog( 7512): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7512): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7512): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7512): [KK AccuPhone]>>> ==============================================================================================
I/EDMNativeHelperService(  814): isMicrophoneEnabled
D/SettingsProvider(  814): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  814): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  814): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  814): selectionArgs: false
D/SettingsProvider(  814): selectionArgs: 10071
D/SecContentProvider(  814): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  814): ret = -1
D/StatusBarManagerService(  814): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/AudioPolicyManager(  287): startInput() input 29
V/AudioPolicyManager(  287): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  287): getNewInputDevice() selected device 80000004
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
V/AudioPolicyManager(  287): DeviceVector::refreshTypes() mDeviceTypes 80000004
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
V/AudioPolicyManager(  287): DeviceVector::getDevicesFromType() for type 80000004 found 0xb295b3c0
V/audio_hw_primary(  287): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  287): in_set_parameters: exit: status(11)
V/AudioPolicyManager(  287): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  287): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1552): mic_started gfk@1e84d306
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/daemonapp( 1315): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/ResourcesManager( 7521): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/ResourcesManager( 7521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/msm8974_platform(  287): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  287): start_input_stream: enter: usecase(7)
V/voice   (  287): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  287): start_input_stream: usecase(7)
D/PreProcess(  287): new SamsungRecord
D/PreProcess(  287): new NS
I/samsungRecord(  287): [samsungrecord] SamsungRecInit 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
I/samsungRecord(  287): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  287): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  287): 1
D/SamsungRecord_NS(  287): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  287): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  287): select_devices: ENTER
,V/audio_hw_primary(  287): select_devices: usecase(normal)
V/audio_hw_primary(  287): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  287): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  287): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  287): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  287): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  287): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  287): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  287): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  287): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  287): ACDB -> send_adm_topology
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  287): ACDB -> send_asm_topology
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  287): ACDB -> send_audtable
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/        (  287): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  287): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  287): ACDB -> send_audvoltable
D/ACDB-LOADER(  287): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  287): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  287): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  287): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  287): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  287): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  287): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: DEC2 Volume
D/audio_route(  287): Setting mixer control: value: 106
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/audio_route(  287): Setting mixer control: SLIM TX7 MUX, value: 9
,D/audio_route(  287): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  287): Setting mixer control: value: 1
D/audio_route(  287): Setting mixer control: DEC2 MUX, value: 1
,D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  287): enable_audio_route: apply mixer path: audio-record
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  287): Setting mixer control: value: 1
,D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): enable_audio_route: exit
V/audio_hw_primary(  287): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/audio_hw_primary(  287): start_input_stream: exit
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/daemonapp( 1315): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/accuweather( 2275): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1315): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,E/Zygote  ( 7553): MountEmulatedStorage()
,E/Zygote  ( 7553): v2
I/libpersona( 7553): KNOX_SDCARD checking this for 10103
I/libpersona( 7553): KNOX_SDCARD not a persona
,I/ActivityManager(  814): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7553 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  814): Killing 6576:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,I/SELinux ( 7553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/HotwordWorker( 1552): onReady
,I/SELinux ( 7553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7553): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/accuweather( 2275): [KK AccuPhone]>>> SM:442 [0:0] updateView iSA = false, mCI = 0, mSL = null , cls = 0 , cls = 1
,D/accuweather( 2275): [KK AccuPhone]>>> SM:447 [0:0] bg transparency val = 0
,D/accuweather( 2275): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
,D/accuweather( 2275): [KK AccuPhone]>>> SM:1044 [0:0] setLayoutContentEmptyMsg = 2131558522
,D/accuweather( 2275): [KK AccuPhone]>>> U:1012 [0:0] icon = 99, isDay = true, type = 261
,D/accuweather( 2275): [KK AccuPhone]>>> U:1187 [0:0] resID = 2130837848
D/accuweather( 2275): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
V/BitmapFactory( 1490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic.png
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/TimaKeyStoreProvider( 7553): TimaSignature is unavailable
,D/ActivityThread( 7553): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,W/libprocessgroup(  814): failed to open /acct/uid_10075/pid_6576/cgroup.procs: No such file or directory
,D/ResourcesManager( 7553): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
,W/ResourcesManager( 7553): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7553): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/SurfaceWidget.Renderer( 2275): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/accuweather( 2275): [KK AccuPhone]>>> SM:1072 [0:0] complete setLayoutContentEmptyMsg Content
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,I/ActivityManager(  814): Killing 6597:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,D/SurfaceWidget.Renderer( 2275): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2275): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2275): [237392/6] SurfaceWidget drawing first frame
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,D/CustomFrequencyManagerService(  814): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  tag : ACTIVITY_RESUME_BOOSTER@6
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,W/ActivityManager(  814): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  814): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/Zygote  ( 7569): MountEmulatedStorage()
E/Zygote  ( 7569): v2
I/libpersona( 7569): KNOX_SDCARD checking this for 10113
I/libpersona( 7569): KNOX_SDCARD not a persona
,I/ActivityManager(  814): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=7569 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  814): Killing 6636:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/SELinux ( 7569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/SurfaceWidget.Renderer( 2275): [237392/6] SurfaceWidget drawing first frame
,I/SELinux ( 7569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/TimaKeyStoreProvider( 7569): TimaSignature is unavailable
,D/ActivityThread( 7569): Added TimaKeyStore provider
,D/ResourcesManager( 7569): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
,W/libprocessgroup(  814): failed to open /acct/uid_1000/pid_6597/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/libprocessgroup(  814): failed to open /acct/uid_1000/pid_6636/cgroup.procs: No such file or directory
,I/Timeline(  814): Timeline: Activity_windows_visible id: ActivityRecord{ec5788e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:98992
,I/ActivityManager(  814): Killing 6757:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,W/ScreenOrientationListener( 7401): Removing an inexistent observer!
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,W/GeoLookout( 7569): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
,I/GeoLookout( 7569): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
,W/libprocessgroup(  814): failed to open /acct/uid_10015/pid_6757/cgroup.procs: No such file or directory
,D/SettingsProvider(  814): name = safetycare_geolookout_registering
D/SettingsProvider(  814): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  814): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  814): selectionArgs: false
D/SettingsProvider(  814): selectionArgs: 10113
D/SecContentProvider(  814): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  814): ret = -1
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/GeoLookout( 7569): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/Zygote  ( 7586): MountEmulatedStorage()
E/Zygote  ( 7586): v2
I/libpersona( 7586): KNOX_SDCARD checking this for 10154
I/libpersona( 7586): KNOX_SDCARD not a persona
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,I/ActivityManager(  814): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7586 uid=10154 gids={50154, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/ActivityManager(  814): Killing 6778:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SELinux ( 7586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,W/libprocessgroup(  814): failed to open /acct/uid_10016/pid_6778/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7586): TimaSignature is unavailable
,D/ActivityThread( 7586): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/ResourcesManager( 7586): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,W/ResourcesManager( 7586): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/ResourcesManager( 7586): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7586): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
W/ResourcesManager( 7586): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
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
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7601): MountEmulatedStorage()
I/libpersona( 7601): KNOX_SDCARD checking this for 10158
E/Zygote  ( 7601): v2
I/libpersona( 7601): KNOX_SDCARD not a persona
,I/ActivityManager(  814): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7601 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  814): Killing 6795:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  814): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 814  tag : ACTIVITY_RESUME_BOOSTER@10
,I/SELinux ( 7601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  814): failed to open /acct/uid_1000/pid_6795/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7601): TimaSignature is unavailable
,D/ActivityThread( 7601): Added TimaKeyStore provider
,D/ResourcesManager( 7601): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/TaskCloserActivity( 7601): TaskCloserActivity enter()
,V/TaskCloserActivity( 7601): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/ActivityManager(  814): Killing 6556:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  814): failed to open /acct/uid_10034/pid_6556/cgroup.procs: No such file or directory
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/TaskPersister(  814): removeObsoleteFile: deleting file=11_task_thumbnail.png
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/SMD     (  281): DCD ON
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  814): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  814): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
D/lights  (  814): lcd : 1 +
,D/lights  (  814): lcd : 1 -
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  814): CMD_RSSI_POLL : out!
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/Watchdog(  814): !@Sync 3
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/SMD     (  281): DCD ON
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 7569): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  814): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  814): CMD_RSSI_POLL : out!
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1167): applyOpen
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
E/SMD     (  281): DCD ON
D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
,D/DisplayPowerController(  814): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  814): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  814): Nap time (uid 1000)...
,I/PowerManagerService(  814): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  814): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  814): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/InputManager-JNI(  814): setDeviceInteractive: 0
,D/PowerManagerService(  814): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  814): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  814): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  814): handleSandman : startDream()
,E/PowerManagerService(  814): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  814): Sleeping (uid 1000)...
D/PowerManagerService(  814): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  814): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  814): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  814): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  814): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  814): 	.unregisterCallback : 1, client=
,D/SContextService(  814): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3b24f67, Service = Auto Rotation, used = 1
,W/CAE     (  814): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  814): stop(ContextProvider.java:149)
,V/CAE     (  814): clear(AutoRotationRunner.java:182)
,V/CAE     (  814): disable(AutoRotationRunner.java:171)
,I/CAE     (  814): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  814): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  293): sendContextData: -78, 7, 0, 0
,D/CAE     (  814): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  814): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  814): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  814): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  814): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  814): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  814): removeSContextService() : service = Auto Rotation
D/SContextService(  814): ===== SContext Service List =====
,D/SContextManager(  814):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@fc91bf9, service=Auto Rotation
,D/DisplayPowerController(  814): ColorFade: onAnimationStart
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1167): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1167): *** KeyguardEffectView getInstanceIfExists ***
,D/lights  (  814): lcd : 0 +
D/DisplayPowerController(  814): getFinalBrightness : 8 -> 0
,D/Launcher.HomeView( 1490): onPause
,D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/KeyguardEffectViewController( 1167): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1167): notifyScreenOffLocked
,D/lights  (  814): lcd : 0 -
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/KeyguardViewMediator( 1167): timeout : 5000
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,V/TaskCloserActivity( 7601): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/KeyguardViewMediator( 1167): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1167): handleNotifyScreenOff
,D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/LightSensor(  814): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  814): mCallbacks.updateBrightness()
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/DisplayPowerController(  814): getFinalBrightness : 8 -> 0
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
,D/StatusBarManagerService(  814): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/StatusBar.NetworkController( 1167): applyOpen
D/StatusBar.NetworkController( 1167): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1167): applyOpen
D/LockPatternUtilsCache( 1167): value : false
,D/LightsService(  814): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 814) 
D/LightsService(  814): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  814): [SvcLED]  onSensorChanged::light value = 0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/SensorManager(  814): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  814): unregisterListener ::   
D/lights  (  814): led_pattern : 5 +
,D/BatteryService(  814): turn on LED for fully charged
,D/Launcher.HomeView( 1490): onStop
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2275): [237392/6] Surface widget pause on instance = 1
,D/lights  (  814): led_pattern : 5 -
D/LightsService(  814): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/accuweather( 2275): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2275): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2275): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
,D/accuweather( 2275): [KK AccuPhone]>>> WR:132 [0:0] onPause
,D/accuweather( 2275): [KK AccuPhone]>>> SM:538 [0:0] onPause
,I/MicrophoneInputStream( 1552): mic_close gfk@1e84d306
,V/AudioPolicyManager(  287): stopInput() input 29
,V/AudioPolicyManager(  287): releaseInput() 29
,V/AudioPolicyManager(  287): closeInput(29)
I/HotwordRecognitionRnr( 1552): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1552): Hotword detection finished
,V/audio_hw_primary(  287): in_standby: enter
,V/BitmapFactory( 1490): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic_none.png
,I/CAE     (  814): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  814): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  814): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  814): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  293): sendContextData: -76, 13, -46, 0
,I/CAE     (  814): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 18, 12, 30,
D/SensorHubManager(  814): SendSensorHubData: send data = -63, 14, 18, 12, 30
,D/Sensorhubs(  293): sendContextData: -63, 14, 18, 12, 30
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  814):  handler : SCREEN_OFF end 
,V/audio_hw_primary(  287): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  287): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  287): disable_audio_route: reset mixer path: audio-record
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  287): Setting mixer control: value: 0
,D/NotificationService(  814): ACTION_SCREEN_OFF
,D/LightsService(  814): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 814) 
D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): disable_audio_route: exit
V/audio_hw_primary(  287): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  287): ++++ audio_route_update_mixer ==============
D/audio_route(  287): Setting mixer control: DEC2 Volume
D/audio_route(  287): Setting mixer control: value: 0
D/WifiStateMachine(  814): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  814): handleScreenStateChanged Exit: false
,D/LightsService(  814): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/audio_route(  287): Setting mixer control: SLIM TX7 MUX, value: 0
,D/LightsService(  814): [SvcLED]  onSensorChanged::light value = 0
D/audio_route(  287): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  287): Setting mixer control: value: 0
,E/WifiStateMachine(  814): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  814): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  814): do suspend true
D/audio_route(  287): Setting mixer control: DEC2 MUX, value: 0
,D/audio_route(  287): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  287): stop_input_stream: exit: status(0)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
,D/SensorManager(  814): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
V/audio_hw_primary(  287): adev_close_input_stream
D/SensorManager(  814): unregisterListener ::   
V/audio_hw_primary(  287): in_standby: enter
V/audio_hw_primary(  287): in_standby: exit:  status(0)
E/audio_hw_primary(  287): adev_close_input_stream, set jack_in to null
D/LightsService(  814): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,V/AudioPolicyManager(  287): releaseInput() exit
,D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  287): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  287): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  814): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  814): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  814): Bridge Server is not available
,D/VolumePanel( 1167): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1167): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1167): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1167): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/DisplayPowerState(  814): !@ ColorFade entry
,D/DisplayPowerController(  814): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  814): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/AutomaticBrightnessController(  814): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  814): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  814): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  814): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  814): unregisterListener ::   
,E/Sensors (  814): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/PersonaManagerService(  814): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  814): MSG_ACTION_SCREEN_OFF called
,D/SensorManager(  814): unregisterListener ::   
,D/NfcService( 1470): call the applyRotuiing
,D/DisplayPowerController(  814): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  814): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
I/DisplayManagerService(  814): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  814): Display changed displayId=0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/STATUSBAR-PhoneStatusBar( 1167):      ACTION_SCREEN_OFF is finished!!!! 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,E/StatusBar( 1167): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1167): dismissHelpPopup 
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/StatusBar.NetworkController( 1167): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/accuweather( 2275): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/StatusBar.NetworkController( 1167): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/accuweather( 2275): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/StatusBar.NetworkController( 1167): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/accuweather( 2275): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  814): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,W/ActivityManager(  814): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  814): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  814): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  814): SIOP:: AP = 370, PST = 430, CUR = 300
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  271): 
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  814): Excessive delay in setPowerMode(): 283ms
D/PowerManagerService(  814): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  814): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  814): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  814): Got set_interactive hint
,I/PowerManagerService(  814): [PWL] Off : 0s ago
I/PowerManagerService(  814): [PWL]   PowerManagerService.Display: ref count=2
,I/PowerManagerService(  814): [PWL]     mDisplayReady : false
D/DisplayPowerController(  814): getFinalBrightness : 0 -> 0
D/PowerManagerService(  814): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  814): [PWL] sb release: PowerManagerService.Display
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardViewMediator( 1167): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1167): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/KeyguardViewMediator( 1167): doKeyguard: not showing because lockscreen is off
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 5s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/FactoryTest( 6476): Not factory mode
,D/FactoryTest( 6476): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6476): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6476): still no open session command from host, so toast
,W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6476): Timeline: Activity_launch_request id:com.android.settings time:114637
,E/PersonaManagerService(  814): inState():  stateMachine is null !!
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  814): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  814): mDVFSHelper.acquire()
,D/FocusedStackFrame(  814): Set to : 0
,V/ActivityManager(  814): Display changed displayId=0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/ConnectivityService(  814): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6476): started activity for popup
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,I/SQLiteSecureOpenHelper( 3540): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3540): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6476): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6476): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6476): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6476): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6476): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6476): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6476): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame(  814): Set to : 0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/InputMethodManagerService(  814): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  814): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@cdc8525 attribute=android.view.inputmethod.EditorInfo@a1426fa, token = android.os.BinderProxy@176f3ae0
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6476): dev.kiessupport is : TRUE
,D/Activity( 6476): performCreate Call secproduct feature valuefalse
D/Activity( 6476): performCreate Call debug elastic valuetrue
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  814): waitForAlarm result :8
,D/SSRM:m  (  814): SIOP:: AP = 340, PST = 417, CUR = 300
,D/ConnectivityService(  814): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  814): mDVFSHelper.release()
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  814): waitForAlarm result :4
,W/Search.LoginHelper( 1552): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  814): stay LED for fully charged
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6678): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6678): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6678): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  814): [PWL] Off : 15s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/ConnectivityService(  814): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  814): SIOP:: AP = 330, PST = 401, CUR = 300
,D/X       (  814): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/SMD     (  281): DCD ON
,D/ContentApp( 1215):  LEVEL : -1
,E/Zygote  ( 7722): MountEmulatedStorage()
,I/ActivityManager(  814): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7722 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,E/Zygote  ( 7722): v2
,I/libpersona( 7722): KNOX_SDCARD checking this for 10054
,I/libpersona( 7722): KNOX_SDCARD not a persona
,I/SELinux ( 7722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7722): TimaSignature is unavailable
,D/ActivityThread( 7722): Added TimaKeyStore provider
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ResourcesManager( 7722): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7722): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7722): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7722): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7722): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7722): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 7722): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 7722): core_num = 4
,W/linker  ( 7722): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 7722): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 7722): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 7722): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 7722):  SIOP_LEVEL: -1
,I/ActivityManager(  814): Killing 4790:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  814): stay LED for fully charged
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/libprocessgroup(  814): failed to open /acct/uid_10035/pid_4790/cgroup.procs: No such file or directory
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  814): !@Sync 4,
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,D/SSRM:m  (  814): SIOP:: AP = 320, PST = 384, CUR = 300
,I/PowerManagerService(  814): [PWL] Off : 30s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  281): DCD ON
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/art     ( 1711): Explicit concurrent mark sweep GC freed 27837(1699KB) AllocSpace objects, 14(1134KB) LOS objects, 39% free, 17MB/29MB, paused 470us total 62.200ms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6678): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6678): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6678): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 320, PST = 370, CUR = 300
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 50s ago
,I/PowerManagerService(  814): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  814): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  814): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=814, ws=WorkSource{10135}) (elapsedTime=218)
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1711): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,D/SSRM:m  (  814): SIOP:: AP = 310, PST = 359, CUR = 300
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): 	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29)
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): 	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 157431, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  814): Explicit concurrent mark sweep GC freed 55708(3MB) AllocSpace objects, 29(1939KB) LOS objects, 29% free, 39MB/55MB, paused 1.878ms total 264.691ms
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  814): waitForAlarm result :4
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6678): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6678): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6678): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  814): !@Sync 5
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 310, PST = 348, CUR = 300,
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 310, PST = 338, CUR = 300
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1711): Vacuum at: now=1449598424147 tag=VacuumService
,I/GoogleURLConnFactory( 1711): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1711): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1711): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1711): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1711): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/System.out( 1711): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1711): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1711): (HTTPLog)-Thread-200-1035690233: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1711): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1711, getuid(): 10012
,I/qtaguid ( 1711): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1711, getuid(): 10012
,W/Uploader( 1711): No account for auth token provided
,I/qtaguid ( 1711): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1711, getuid(): 10012
,E/SMD     (  281): DCD ON
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1711): No account for auth token provided
,I/qtaguid ( 1711): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1711, getuid(): 10012
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6678): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6678): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6678): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1711): No account for auth token provided
,I/qtaguid ( 1711): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1711, getuid(): 10012
,W/Uploader( 1711): No account for auth token provided
,I/qtaguid ( 1711): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1711, getuid(): 10012
,W/Uploader( 1711):  no longer exists, so no auth token.
,I/qtaguid ( 1711): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1711, getuid(): 10012
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  814): [PWL] Off : 75s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7325): Starting books sync, d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1711): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,D/SSRM:m  (  814): SIOP:: AP = 310, PST = 331, CUR = 300
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3628140564827926936&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3628140564827926936&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3628140564827926936&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,E/BooksSync( 7325): Soft error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3628140564827926936&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7325): Sync error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3628140564827926936&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7325): Finished books sync
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161981, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  814): mCursor = null
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  814): !@Sync 6
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,D/SSRM:m  (  814): SIOP:: AP = 310, PST = 323, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 316, CUR = 300
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 105s ago
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 312, CUR = 300
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog(  814): !@Sync 7
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 309, CUR = 300
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 307, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 140s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 305, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  814): !@Sync 8
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 302, CUR = 300
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 9
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,I/PowerManagerService(  814): [PWL] Off : 180s ago
I/PowerManagerService(  814): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  814): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  814): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=814, ws=WorkSource{10135}) (elapsedTime=453)
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): 	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29)
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): 	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 286921, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  814): Explicit concurrent mark sweep GC freed 49598(2MB) AllocSpace objects, 47(1207KB) LOS objects, 29% free, 38MB/54MB, paused 1.252ms total 95.737ms
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  281): DCD ON
,D/TimaService(  814): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  814): TimaServiceHandler.handleMessage what =1
,D/TimaService(  814): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  814): initializing...
,I/TLC_TIMA_PKM_initialize(  814): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  814): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  814): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  814): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  814): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  814): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  814): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  814): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  814): App is not loaded in QSEE
,D/QSEECOMAPI: (  814): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  814): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  814): Trustlet response is completed
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  814): !@Sync 10
,E/SMD     (  281): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 225s ago
,V/AlarmManager(  814): waitForAlarm result :4
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0,
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,E/Zygote  ( 7969): MountEmulatedStorage()
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7969): v2
,I/libpersona( 7969): KNOX_SDCARD checking this for 10081
I/libpersona( 7969): KNOX_SDCARD not a persona
,I/ActivityManager(  814): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7969 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,I/SELinux ( 7969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,I/SELinux ( 7969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SELinux ( 7969): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7969): TimaSignature is unavailable
,D/ActivityThread( 7969): Added TimaKeyStore provider
,D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  814): Killing 6812:com.policydm/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  814): failed to open /acct/uid_1000/pid_6812/cgroup.procs: No such file or directory
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 299, CUR = 300,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  814): !@Sync 11
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7325): Starting books sync, d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1711): Explicit concurrent mark sweep GC freed 48665(2MB) AllocSpace objects, 68(4MB) LOS objects, 39% free, 18MB/30MB, paused 3.183ms total 94.334ms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1711): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2463925479156161144&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 298, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2463925479156161144&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2463925479156161144&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/BooksSync( 7325): Soft error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2463925479156161144&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7325): Sync error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2463925479156161144&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7325): Finished books sync
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 322332, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  814): mCursor = null
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  281): DCD ON
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1711): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6678): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6678): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6678): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6678): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6678): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6678): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6678): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6678): Ignoring header User-Agent because its value was null.
,I/System.out( 6678): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6678): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6678): (HTTPLog)-Thread-1098-1038955061: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  814): !@Sync 12
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 275s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 294, CUR = 300
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 13
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  814): stay LED for fully charged
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  814): !@Sync 14
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 330s ago
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  814): !@Sync 15
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/bootchecker(  314): bootchecker wake up!!
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  814): !@Sync 16
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 390s ago
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 17
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  281): DCD ON
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1711): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): 	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29)
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): 	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/EsSyncAdapterService( 6651): Sync failure,
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 545568, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  814): mCursor = null
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON,
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  814): !@Sync 18
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 455s ago
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,I/Atfwd_Daemon(  318): Stop the daemon....
,E/Watchdog(  814): !@Sync 19
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/TimaService(  814): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  814): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  814): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7325): Starting books sync, d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,E/Watchdog(  814): !@Sync 20
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7873451186502947364&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7873451186502947364&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7873451186502947364&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  814): waitForAlarm result :8,
,E/SMD     (  281): DCD ON
,E/BooksSync( 7325): Soft error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7873451186502947364&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7325): Sync error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7873451186502947364&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7325): Finished books sync
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 613124, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  814): Explicit concurrent mark sweep GC freed 64656(4MB) AllocSpace objects, 115(2MB) LOS objects, 29% free, 38MB/54MB, paused 1.646ms total 134.309ms
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  814): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 525s ago,
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  814): !@Sync 21
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 22
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 23
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 600s ago
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 24
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 25
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 680s ago
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 26
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 27
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 28
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 765s ago
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 29
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/TimaService(  814): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  814): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  814): TimaServiceHandler.handleMessage what =1
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 30
,E/SMD     (  281): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/LightsService(  814): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  814): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/SensorManager(  814): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1711): Message class com.google.f.a.a.i
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/EventLogService( 2442): Aggregate from 1449597375035 (log), 1449597375035 (data)
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  814): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  814): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  814): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  814): unregisterListener ::   
D/LightsService(  814): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 31
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  814): [PWL] Off : 855s ago
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 32
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 33
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 34
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 950s ago
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  814): Plugged
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,I/art     ( 1711): Explicit concurrent mark sweep GC freed 38144(2MB) AllocSpace objects, 27(2MB) LOS objects, 40% free, 18MB/30MB, paused 2.305ms total 77.879ms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1711): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): 	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29)
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): 	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 546584, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  814): !@Sync 35
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,E/SMD     (  281): DCD ON
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  814): !@Sync 36
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,I/PhoneStatusBar( 1167): Icon Only
D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 289, CUR = 300
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): 	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29)
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): 	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1093618, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2854): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  814): mCursor = null
,E/Watchdog(  814): !@Sync 37
,I/art     (  814): Explicit concurrent mark sweep GC freed 63761(5MB) AllocSpace objects, 164(3MB) LOS objects, 29% free, 38MB/54MB, paused 1.858ms total 157.112ms
,E/SMD     (  281): DCD ON
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON,
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 289, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 289, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  814): stay LED for fully charged
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/BooksSync( 7325): Starting books sync, d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1711): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 288, CUR = 300
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6559610911496823456&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog(  814): !@Sync 38
,E/SMD     (  281): DCD ON
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6559610911496823456&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7325): Authentication error
E/BooksAccountManager( 7325): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7325): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7325): null auth token
,I/qtaguid ( 7325): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7325, getuid(): 10082
,I/qtaguid ( 7325): Untagging socket 34
,W/ApiaryClient( 7325): Error response from books API: {
W/ApiaryClient( 7325):  "error": {
W/ApiaryClient( 7325):   "errors": [
W/ApiaryClient( 7325):    {
W/ApiaryClient( 7325):     "domain": "global",
W/ApiaryClient( 7325):     "reason": "required",
W/ApiaryClient( 7325):     "message": "Login Required",
W/ApiaryClient( 7325):     "locationType": "header",
W/ApiaryClient( 7325):     "location": "Authorization"
W/ApiaryClient( 7325):    }
W/ApiaryClient( 7325):   ],
W/ApiaryClient( 7325):   "code": 401,
W/ApiaryClient( 7325):   "message": "Login Required"
W/ApiaryClient( 7325):  }
W/ApiaryClient( 7325): }
,W/ApiaryClient( 7325): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6559610911496823456&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7325): Headers suppressed
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  814): waitForAlarm result :8
,E/BooksSync( 7325): Soft error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6559610911496823456&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7325): Sync error
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7325): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6559610911496823456&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7325): Headers suppressed
E/BooksSync( 7325): 
E/BooksSync( 7325): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7325): Finished books sync
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1140167, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  814): mCursor = null
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 1050s ago
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 288, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 288, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 287, CUR = 300
,E/Watchdog(  814): !@Sync 39
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 285, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/TimaService(  814): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  814): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  814): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  814): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  814): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  814): Updating Usage Statistics in DB @ 1449599454987
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
,W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  814): ::getAppControlDB: Exception to create DB
W/System.err(  814): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  814): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  814): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  814): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  814): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  814): Done Updating Usage Statistics in DB @ 1449599455368
,V/AlarmManager(  814): waitForAlarm result :4
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 285, CUR = 300
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): 	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29)
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): 	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  814): !@Sync 40
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1183693, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  814): mCursor = null
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  281): DCD ON
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 286, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 286, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0,
D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 286, CUR = 300
,E/Watchdog(  814): !@Sync 41
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  814): [PWL] Off : 1155s ago
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 285, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 42
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 283, CUR = 300
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 281, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 43
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 44
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 274, CUR = 300
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1711): Explicit concurrent mark sweep GC freed 38646(2MB) AllocSpace objects, 28(2MB) LOS objects, 40% free, 18MB/30MB, paused 475us total 26.988ms
,D/ResourcesManager( 1711): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): 	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29)
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): 	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/art     ( 1167): Explicit concurrent mark sweep GC freed 87091(4MB) AllocSpace objects, 53(4MB) LOS objects, 30% free, 37MB/53MB, paused 429us total 44.612ms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
,I/art     ( 6651): Explicit concurrent mark sweep GC freed 54148(3MB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 1.804ms total 83.892ms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
,D/PanelView( 1167): There is/are notification(s) 
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1334053, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,I/art     (  814): Explicit concurrent mark sweep GC freed 59855(4MB) AllocSpace objects, 80(1865KB) LOS objects, 29% free, 38MB/54MB, paused 1.247ms total 83.188ms
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 274, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 280, PST = 274, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 45
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 1265s ago
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 46
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 47
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 273, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 48
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 49
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 1380s ago
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/TimaService(  814): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  814): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  814): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  814): !@Sync 50
,E/SMD     (  281): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 51
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 52
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
,D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/HttpOperation( 6651): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at dsf.a(PG:807)
E/HttpOperation( 6651): 	at fhk.a(PG:1126)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 8 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 10 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
,D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/AlarmManager(  814): waitForAlarm result :8
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
E/HttpOperation( 6651): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at kff.l(PG:132)
E/HttpOperation( 6651): 	at ieo.a(PG:43)
E/HttpOperation( 6651): 	at iep.a(PG:93)
E/HttpOperation( 6651): 	at fhn.a(PG:59)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
,D/PanelView( 1167): There is/are notification(s) 
E/ExperimentLoader( 6651): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6651): ,	at kfv.a(PG:65)
E/ExperimentLoader( 6651): 	at kff.u(PG:385)
E/ExperimentLoader( 6651): 	at kfb.a(PG:29),
E/ExperimentLoader( 6651): 	at kff.l(PG:132)
E/ExperimentLoader( 6651): 	at ieo.a(PG:43)
E/ExperimentLoader( 6651): ,	at iep.a(PG:93)
E/ExperimentLoader( 6651): 	at fhn.a(PG:59)
,E/ExperimentLoader( 6651): 	at lex.a(PG:85)
E/ExperimentLoader( 6651): 	at lex.b(PG:132)
E/ExperimentLoader( 6651): ,	at fhk.a(PG:1146)
E/ExperimentLoader( 6651): 	at fhk.a(PG:908)
E/ExperimentLoader( 6651): 	,at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6651): 	at ihi.a(PG:22)
E/ExperimentLoader( 6651): 	at kft.a(PG:91)
E/ExperimentLoader( 6651): 	at kfv.a(PG:62)
E/ExperimentLoader( 6651): 	... 12 more
E/ExperimentLoader( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6651): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6651): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6651): 	at ihi.a(PG:19)
E/ExperimentLoader( 6651): 	... 14 more
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1711): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  814): uri = 14 selection = getSealedState
D/SecContentProvider2(  814): mCursor = null
,D/SecContentProvider2(  814): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  814): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1167): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1167): Icon Only
,D/LockPatternUtilsCache( 1167): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1167): value : false
D/PanelView( 1167): There is/are notification(s) 
D/PanelView( 1167): There is/are notification(s) 
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/HttpOperation( 6651): [getaccountstatus] Unexpected exception
E/HttpOperation( 6651): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6651): 	at kfv.a(PG:65)
E/HttpOperation( 6651): 	at kff.u(PG:385)
E/HttpOperation( 6651): 	at kfb.a(PG:29)
E/HttpOperation( 6651): 	at ixd.a(PG:248)
E/HttpOperation( 6651): 	at ixd.b(PG:206)
E/HttpOperation( 6651): 	at ixd.a(PG:175)
E/HttpOperation( 6651): 	at fig.a(PG:78)
E/HttpOperation( 6651): 	at lex.a(PG:85)
E/HttpOperation( 6651): 	at lex.b(PG:132)
E/HttpOperation( 6651): 	at fhk.a(PG:1146)
E/HttpOperation( 6651): 	at fhk.a(PG:908)
E/HttpOperation( 6651): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6651): 	at ihi.a(PG:22)
E/HttpOperation( 6651): 	at kft.a(PG:91)
E/HttpOperation( 6651): 	at kfv.a(PG:62)
E/HttpOperation( 6651): 	... 12 more
E/HttpOperation( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6651): 	at gde.c(Unknown Source)
E/HttpOperation( 6651): 	at gde.b(Unknown Source)
E/HttpOperation( 6651): 	at ihi.a(PG:19)
E/HttpOperation( 6651): 	... 14 more
,E/EsSyncAdapterService( 6651): Sync failure
E/EsSyncAdapterService( 6651): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6651): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6651): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6651): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6651): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6651): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6651): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6651): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6651): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6651): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6651): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6651): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6651): 	... 10 more
E/EsSyncAdapterService( 6651): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6651): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6651): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6651): 	... 12 more
E/EsSyncAdapterService( 6651): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6651): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6651): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6651): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6651): 	... 14 more
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  814): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1575892, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 53
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,V/AlarmManager(  814): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 1500s ago
,E/SMD     (  281): DCD ON
,W/ProcessCpuTracker(  814): Skipping unknown process pid 8537
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 54
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,V/AlarmManager(  814): waitForAlarm result :8
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 55
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 56
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 57
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,D/BatteryService(  814): stay LED for fully charged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,I/PowerManagerService(  814): [PWL] Off : 1625s ago
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 58
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 59
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,D/NetworkStatsFactory(  814): UpdateStatsForKnox
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/TimaService(  814): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  814): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  814): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  814): !@Sync 60
,E/SMD     (  281): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  814): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  814): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  814): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :4
,D/LightsService(  814): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  814): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  814): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
,I/ProcessStatsService(  814): Prepared write state in 25ms
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1167): handleTimeUpdate
,D/KeyguardEffectViewController( 1167): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1167): *** don't update sliding image ***
,V/NetworkStats(  814): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  814): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  814): UpdateStatsForKnox
,D/ConnectivityService(  814): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  814): performPollLocked() took 11ms
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/NtpTrustedTime(  814): currentTimeMillis() cache hit
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
,D/NtpTrustedTime(  814): currentTimeMillis() cache hit
,D/NtpTrustedTime(  814): currentTimeMillis() cache hit
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1167): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1711): Message class com.google.f.a.a.i
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  814): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  814): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  814): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  814): unregisterListener ::   
,D/LightsService(  814): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/ProcessStatsService(  814): Pruning old procstats: /data/system/procstats/state-2015-12-08-07-48-46.bin
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 61
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/ConnectivityService(  814): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  814): [PWL] Off : 1755s ago
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 62
,E/SMD     (  281): DCD ON
,V/AlarmManager(  814): waitForAlarm result :8
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,E/SMD     (  281): DCD ON
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  814): Plugged
,I/MotionRecognitionService(  814): setPowerConnected  = true
,D/BatteryService(  814): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  281): DCD ON
,E/SMD     (  281): DCD ON
,E/Watchdog(  814): !@Sync 63
,E/SMD     (  281): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8600): 
D/AndroidRuntime( 8600): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8600): CheckJNI is OFF
D/AndroidRuntime( 8600): setted country_code = Germany
D/AndroidRuntime( 8600): setted countryiso_code = DE
D/AndroidRuntime( 8600): setted sales_code = DBT
D/AndroidRuntime( 8600): readGMSProperty: start
D/AndroidRuntime( 8600): readGMSProperty: already setted!!
D/AndroidRuntime( 8600): readGMSProperty: end
D/AndroidRuntime( 8600): addProductProperty: start
E/AffinityControl( 8600): AffinityControl: registerfunction enter
D/AndroidRuntime( 8600): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  814): START PACKAGE DELETE: observer{551670315}
D/PackageManager(  814): pkg{<packageName>}
D/PackageManager(  814): user{0}
D/PackageManager(  814): caller{2000}
D/PackageManager(  814): flags{3}
D/PersonaManagerService(  814): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  814): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  814): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  814): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  814): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  814): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  814): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  814): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  814): getApplicationUninstallationEnabled
D/ApplicationPolicy(  814): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  814): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  814): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  814): Killing 7401:com.test.thalitest/u0a367 (adj 15): stop com.test.thalitest
I/ActivityManager(  814): Killing 7512:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1808s
I/ActivityManager(  814): Killing 6853:com.android.mms/u0a50 (adj 15): empty for 1808s
I/ActivityManager(  814): Killing 6008:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1808s
I/ActivityManager(  814): Killing 7480:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1809s
I/ActivityManager(  814): Killing 4983:com.android.defcontainer/u0a5 (adj 15): empty for 1837s
I/ActivityManager(  814): Killing 4733:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1839s
I/ActivityManager(  814): Killing 7215:com.sec.android.app.samsungapps/u0a40 (adj 15): empty for 1844s
I/ActivityManager(  814): Killing 7194:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1844s
I/ActivityManager(  814): Killing 6722:com.google.android.gms:car/u0a12 (adj 15): empty for 1844s
I/ActivityManager(  814): Killing 7177:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1845s
I/ActivityManager(  814): Killing 7136:com.samsung.helphub/1000 (adj 15): empty for 1845s
I/ActivityManager(  814): Killing 7120:com.samsung.android.magazine.service/u0a118 (adj 15): empty for 1845s
I/ActivityManager(  814): Killing 7105:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): empty for 1845s
I/ActivityManager(  814): Killing 7086:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1845s
I/ActivityManager(  814): Killing 7069:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty for 1845s
I/ActivityManager(  814): Killing 7056:com.sec.android.provider.logsprovider/u0a20 (adj 15): empty for 1845s
I/ActivityManager(  814): Killing 6987:com.sec.android.automotive.drivelink/u0a99 (adj 15): empty for 1846s
I/ActivityManager(  814): Killing 7016:com.vlingo.midas/u0a33 (adj 15): empty for 1846s
I/ActivityManager(  814): Killing 6960:com.google.android.apps.docs/u0a98 (adj 15): empty for 1846s
I/ActivityManager(  814): Killing 6614:com.sec.chaton/u0a86 (adj 15): empty for 1847s
I/ActivityManager(  814): Killing 6259:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1847s
I/ActivityManager(  814): Killing 6941:com.sec.android.app.soundalive/u0a58 (adj 15): empty for 1847s
I/ActivityManager(  814): Killing 6918:com.sec.android.app.myfiles/u0a51 (adj 15): empty for 1847s
I/ActivityManager(  814): Killing 6902:com.wsomacp/u0a25 (adj 15): empty for 1847s
I/ActivityManager(  814): Killing 6887:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1847s
I/ActivityManager(  814): Killing 6833:com.osp.app.signin/u0a45 (adj 15): empty for 1849s
I/ActivityManager(  814): Killing 6051:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): empty for 1849s
I/ActivityManager(  814): Killing 5232:com.sec.spp.push/u0a38 (adj 15): empty for 1849s
E/SMD     (  281): DCD ON
D/CountryDetector(  814): No listener is left
W/PackageSettings(  814): Skipping PackageSetting{237bfd0d com.example.hello/10374} due to missing metadata
I/ActivityManager(  814): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
E/libprocessgroup(  814): failed to kill 1 processes for processgroup 7401
I/art     ( 4618): Explicit concurrent mark sweep GC freed 3635(203KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 456us total 25.543ms
I/art     ( 1552): Explicit concurrent mark sweep GC freed 40763(2MB) AllocSpace objects, 3(728KB) LOS objects, 39% free, 16MB/27MB, paused 1.424ms total 63.342ms
D/BatteryService(  814): level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  814): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  814): stay LED for fully charged
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  814): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1869): mOCRHelper is null
W/GeofencerStateMachine( 2205): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
I/art     (  814): Explicit concurrent mark sweep GC freed 66483(6MB) AllocSpace objects, 181(3MB) LOS objects, 29% free, 39MB/55MB, paused 3.544ms total 145.455ms
D/ResourcesManager(  814): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/Zygote  ( 8631): MountEmulatedStorage()
E/Zygote  ( 8631): v2
I/libpersona( 8631): KNOX_SDCARD checking this for 10019
I/libpersona( 8631): KNOX_SDCARD not a persona
I/ActivityManager(  814): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8631 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/SSRM:m  (  814): SIOP:: AP = 270, PST = 272, CUR = 300
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/SELinux ( 8631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/TimaKeyStoreProvider( 8631): TimaSignature is unavailable
D/ActivityThread( 8631): Added TimaKeyStore provider
D/SecContentProvider2(  814): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  814): mCursor = null
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 8631): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/RegisteredServicesCache( 1470): empty dynamic service
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
I/KLMS-2.4.503: ( 8631): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Books/Books.apk
I/KLMS-2.4.503: ( 8631): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449600150907
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.503: ( 8631): MainReciver(): PACKAGE_REMOVED
D/EnterpriseDeviceManagerService(  814): Package has changed for user 0
D/EnterpriseDeviceManagerService(  814): Admin package name: com.google.android.gms
I/KLMS-2.4.503: ( 8631): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/art     (  814): Explicit concurrent mark sweep GC freed 13213(632KB) AllocSpace objects, 2(32KB) LOS objects, 29% free, 39MB/55MB, paused 3.065ms total 283.852ms
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/libpersona( 8646): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8646): MountEmulatedStorage()
I/libpersona( 8646): KNOX_SDCARD not a persona
E/Zygote  ( 8646): v2
D/PackageManager(  814): delete codoeFile: 
I/ActivityManager(  814): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8646 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  814): Killing 7521:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): empty for 1809s
D/PackageManager(  814): result of delete: 1{551670315}
I/SELinux ( 8646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8646): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 8600): Shutting down VM
D/TimaKeyStoreProvider( 8646): TimaSignature is unavailable
D/ActivityThread( 8646): Added TimaKeyStore provider
D/ResourcesManager(  814): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 8646): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/RCPManagerService(  814): PackageReceiver onReceive()
I/HarmonyEASService(  814): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14451( 8646): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8646): ELMEngine.ELMEngine( context ).
D/elm:14451( 8646): MDMBridge.setEnterpriseBridge()
D/KnoxMUMContainerPolicy(  814): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:14451( 8646): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8646): ElmAgentService : onCreate()
D/elm:14451( 8646): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/BatteryService(  814): Sending ACTION_BATTERY_CHANGED.
D/elm:14451( 8646): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8646): MDMBridge.getInstance()
D/elm:14451( 8646): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14451( 8646): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
E/Zygote  ( 8664): MountEmulatedStorage()
E/Zygote  ( 8664): v2
I/libpersona( 8664): KNOX_SDCARD checking this for 10017
I/libpersona( 8664): KNOX_SDCARD not a persona
I/ActivityManager(  814): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8664 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/BackupManagerService(  814): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/SELinux ( 8664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/JobSchedulerService(  814): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  814): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  814): uID is 10367
V/EnterpriseBillingPolicy(  814): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  814): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  814): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  814): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  814): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  814): getBillingProfileForVpnEngine - start - com.test.thalitest
I/SELinux ( 8664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/KeyguardUpdateMonitor( 1167): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1167): handleBatteryUpdate
E/SELinux ( 8664): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/STATUSBAR-PhoneStatusBar( 1167):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/EnterpriseBillingPolicyStorage(  814): getBillingProfileForVpnEngine - end - null
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3241): Disconnected process message: 10
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     (  309): Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 912us total 32.925ms
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/elm:14451( 8646): ElmAgentService : onDestroy().
D/TaskPersister(  814): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  814): removeObsoleteFile: deleting file=12_task_thumbnail.png
I/ActivityManager(  814): Killing 7553:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): empty for 1809s
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1167): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 790us total 23.935ms
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/TimaKeyStoreProvider( 8664): TimaSignature is unavailable
D/ActivityThread( 8664): Added TimaKeyStore provider
D/MotionRecognitionService(  814):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  814): Plugged
I/MotionRecognitionService(  814): setPowerConnected  = true
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 8664): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 840us total 22.246ms
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8664): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8664): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8664): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  814): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
E/Zygote  ( 8679): MountEmulatedStorage()
E/Zygote  ( 8679): v2
I/libpersona( 8679): KNOX_SDCARD checking this for 1000
I/libpersona( 8679): KNOX_SDCARD not a persona
I/ActivityManager(  814): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8679 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/ActivityManager(  814): Killing 7569:com.sec.android.GeoLookout/u0a113 (adj 15): empty for 1808s
I/SELinux ( 8679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/ResourcesManager(  814): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/SELinux ( 8679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/ResourcesManager(  814): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  814): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/SELinux ( 8679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  814): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/TimaKeyStoreProvider( 8679): TimaSignature is unavailable
D/ResourcesManager(  814): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ActivityThread( 8679): Added TimaKeyStore provider
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 8679): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
I/PCWCLIENTTRACE_LOG( 8679): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8679): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8679): new DMDBOpenHelper instance
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteDatabase( 8679): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase( 8679): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8679): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8679): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8679): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8679): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase( 8679): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8679): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8679): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 8679): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 8679): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 8679): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8679): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 8679): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8679): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8679): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8679): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8679): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8679): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8679): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 8679): Shutting down VM
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  814): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
E/AndroidRuntime( 8679): FATAL EXCEPTION: main
E/AndroidRuntime( 8679): Process: com.sec.pcw.device, PID: 8679
E/AndroidRuntime( 8679): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8679): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8679): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8679): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8679): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8679): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8679): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8679): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8679): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8679): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8679): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8679): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8679): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8679): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8679): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 8679): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8679): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8679): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime( 8679): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8679): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8679): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8679): 	... 11 more
V/ApplicationPolicy(  814): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
F/libc    (  814): Fatal signal 7 (SIGBUS), code 2, fault addr 0x75904ef2 in tid 8696 (Error dump: sys)
F/libc    (  814): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa10b23a0 in tid 1636 (Binder_D)
W/Resources(  814): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
F/libc    (  814): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2134): File locking failed. error= Bad file number
E/audit_log( 2134): File locking failed. error= Bad file number
E/audit_log( 2134): File locking failed. error= Bad file number
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
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'country_detector' died
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
I/ServiceManager(  247): service 'backup' died
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
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
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
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
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
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
W/Sensors ( 1298): sensorservice died [0x9d8212c0]
W/Sensors ( 2205): sensorservice died [0xaf0c3ec0]
W/Sensors ( 1480): sensorservice died [0xaf0c5340]
W/Sensors ( 1167): sensorservice died [0xaf0d2080]
W/AudioFlinger(  287): power manager service died !!!
W/AudioFlinger(  287): power manager service died !!!
W/Sensors ( 1490): sensorservice died [0xaf0c53c0]
E/WifiManager( 1167): Channel connection lost

```
