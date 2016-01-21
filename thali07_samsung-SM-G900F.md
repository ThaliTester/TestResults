#### Test 568182548138a64_thali07_samsung-SM-G900F Logs


```
--------- beginning of main,
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
E/SMD     (  287): DCD ON
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 7426): 
D/AndroidRuntime( 7426): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7426): CheckJNI is OFF
D/AndroidRuntime( 7426): setted country_code = Germany
D/AndroidRuntime( 7426): setted countryiso_code = DE
D/AndroidRuntime( 7426): setted sales_code = DBT
D/AndroidRuntime( 7426): readGMSProperty: start
D/AndroidRuntime( 7426): readGMSProperty: already setted!!
D/AndroidRuntime( 7426): readGMSProperty: end
D/AndroidRuntime( 7426): addProductProperty: start
I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7374): null auth token
D/PanelView( 1169): There is/are notification(s) 
I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
I/qtaguid ( 7374): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
I/qtaguid ( 7374): Untagging socket 34
W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
W/ApiaryClient( 7374): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8475213707967938378&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/AffinityControl( 7426): AffinityControl: registerfunction enter
D/AndroidRuntime( 7426): Calling main entry com.android.commands.am.Am
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
E/PersonaManagerService(  804): inState():  stateMachine is null !!
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  804): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  804): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  804): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  804): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3822): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 69
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3822): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3822): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
D/AndroidRuntime( 7426): Shutting down VM
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3822): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3822): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
D/LightsService(  804): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 804) 
D/LightsService(  804): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  804): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  804): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1169): Icon Only
D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  804): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3822): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3822): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/KnoxNotification( 1169): ----- inflateViews : modified publicViewLocal -----
E/Zygote  ( 7448): MountEmulatedStorage()
E/Zygote  ( 7448): v2
I/libpersona( 7448): KNOX_SDCARD checking this for 10200
D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
I/libpersona( 7448): KNOX_SDCARD not a persona
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
I/ActivityManager(  804): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7448 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1169): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@17d3d03d
D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1169): Icon Only
I/SELinux ( 7448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7448): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
D/TimaKeyStoreProvider( 7448): TimaSignature is unavailable
D/ActivityThread( 7448): Added TimaKeyStore provider
V/ActivityManager(  804): Display changed displayId=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  804): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 7448): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 7448): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7448): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 7448): Loading: webviewchromium
I/LibraryLoader( 7448): Time to load native libraries: 2 ms (timestamps 5617-5619)
I/LibraryLoader( 7448): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/WebViewChromiumFactoryProvider( 7448): Binding Chromium to main looper Looper (main, tid 1) {113e3306}
I/LibraryLoader( 7448): Expected native library version number "",actual native library version number ""
I/chromium( 7448): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7448): Initializing chromium process, renderers=0
W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7448): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7448): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7448): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Adreno-EGL( 7448): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7448): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7448): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7448): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7448): Remote Branch: 
I/Adreno-EGL( 7448): Local Patches: 
I/Adreno-EGL( 7448): Reconstruct Branch: 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/chromium( 7448): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7448): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7448): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SystemWebViewEngine( 7448): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7448): Attempt to remove local handle scope entry from IRT, ignoring
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
D/Activity( 7448): performCreate Call secproduct feature valuefalse
D/Activity( 7448): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/OpenGLRenderer( 7448): Render dirty regions requested: true
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ActivityManager(  804): post active user change for 0
D/KnoxTimeoutHandler(  804): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  804): handleActiveUserChange for user 0
I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
I/OpenGLRenderer( 7448): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 7448): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7448): Enabling debug mode 0
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
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
D/InputMethodManagerService(  804): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  804): Displayed com.test.thalitest/.MainActivity: +659ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Timeline( 7448): Timeline: Activity_idle id: android.os.BinderProxy@14c6d51 time:96039
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
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
D/JsMessageQueue( 7448): Set native->JS mode to OnlineEventsBridgeMode
E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7374): null auth token
I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/chromium( 7448): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7448): 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/qtaguid ( 7374): Untagging socket 34
W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
W/ApiaryClient( 7374): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8475213707967938378&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/CustomFrequencyManagerService(  804): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  804): mDVFSHelper.release()
I/Timeline(  804): Timeline: Activity_windows_visible id: ActivityRecord{105f2396 u0 com.test.thalitest/.MainActivity t18} time:96210
D/CustomFrequencyManagerService(  804): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  pkgName : ACTIVITY_RESUME_BOOSTER@10
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/jxcore_app_log( 7448): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259382784
E/Adreno-ES20( 7448): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7448): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/chromium( 7448): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  804): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/BooksSync( 7374): Soft error
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8475213707967938378&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7374): Headers suppressed
E/BooksSync( 7374): 
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7374): Sync error
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8475213707967938378&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7374): Headers suppressed
E/BooksSync( 7374): 
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7374): Finished books sync
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  804): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63661, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  804): Killing 6329:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  804): mCursor = null
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  804): failed to open /acct/uid_10117/pid_6329/cgroup.procs: No such file or directory
,I/art     (  804): Explicit concurrent mark sweep GC freed 29848(1585KB) AllocSpace objects, 11(1651KB) LOS objects, 29% free, 37MB/53MB, paused 1.809ms total 110.281ms
,D/PowerManagerService(  804): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/ProcessCpuTracker(  804): Skipping unknown process pid 7513
W/ProcessCpuTracker(  804): Skipping unknown process pid 7514
,W/ProcessCpuTracker(  804): Skipping unknown process pid 7516
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/jxcore-log( 7448): Initializing JXcore engine
W/jxcore-log( 7448): JXcore engine is ready
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/auditd  ( 2060): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  804): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  804): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 7448): Starting JXcore engine
,E/Zygote  ( 7520): MountEmulatedStorage()
E/Zygote  ( 7520): v2
I/libpersona( 7520): KNOX_SDCARD checking this for 1000
I/libpersona( 7520): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7520 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/GAV2    ( 7374): Thread[GAThread,5,main]: No campaign data found.
,I/art     (  313): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 11.540ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 7.755ms
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SELinux ( 7520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7520): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 12.854ms
,D/TimaKeyStoreProvider( 7520): TimaSignature is unavailable
,D/ActivityThread( 7520): Added TimaKeyStore provider
,D/ResourcesManager( 7520): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7520):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7520):  SeDenialReceiver : File path = null
W/jxcore-log( 7448): Platform android
W/jxcore-log( 7448): 
,W/jxcore-log( 7448): Process ARCH arm
W/jxcore-log( 7448): 
I/ActivityManager(  804): Killing 6587:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,W/libprocessgroup(  804): failed to open /acct/uid_10075/pid_6587/cgroup.procs: No such file or directory
,D/SSRM:m  (  804): SIOP:: AP = 400, PST = 435, CUR = 300
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,V/AlarmManager(  804): waitForAlarm result :4
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7537): MountEmulatedStorage()
I/libpersona( 7537): KNOX_SDCARD checking this for 10179
E/Zygote  ( 7537): v2
I/libpersona( 7537): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7537 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 7537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7537): TimaSignature is unavailable
,D/ActivityThread( 7537): Added TimaKeyStore provider
,D/ResourcesManager( 7537): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/ResourcesManager( 7537): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/UMC:Core( 7537): onCreate(): 
,D/USER_AGENT( 7537): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,D/[SAMSUNG SMARCART NATIVE]( 7537): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7537): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7537): ================================================
I/CSTORAGE( 7537):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7537): ================================================
,I/TZ_CCM_C_GetFunctionList: ( 7537): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7537): FINISHED: initialize rv:0
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7448): JXcore Cordova bridge is ready!
I/jxcore-log( 7448): 
,W/jxcore-log( 7448): JXcore engine is started
,D/UMC:SecurityUtils( 7537): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7537): Loaded server certificates: 0
D/UMC:SecurityUtils( 7537): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7537): New Flow
,D/TimaService(  804): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  804): TIMA: in getTimaVersion
,I/        (  804): CCM JNI: In ccm_register_for_default_cert
I/        (  804): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  804): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  804): pInitArgs 0x6eda8814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  804): &ctx = 0x9feb2c1c
I/TLC_TZ_CCM: (  804): creating new ccm context...
I/TLC_TZ_CCM: (  804): initializing ccm context...
I/TLC_TZ_CCM: (  804): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  804): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  804): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  804): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  804): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  804): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  804): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  804): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  804): Client_Server_Open was called
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/TZ: client_server_communication(  804): IClientServer::IClientServer()
I/TZ: client_server_communication(  804): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  804): IClientServer::~IClientServer()
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1075): OPENSWCONN
I/TZ_CCM_SERVER( 1075): creating new ccm context...
I/TZ_CCM_SERVER( 1075): initializing ccm context...
I/TZ_CCM_SERVER( 1075): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1075): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1075): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1075): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1075): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1075): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1075): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1075): QSEECom_get_handle sb_length = 0x9800
,D/QSEECOMAPI: ( 1075): App is not loaded in QSEE
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QSEECOMAPI: ( 1075): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication( 1075): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  804): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  804): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  804): ctx = 0x6e89b8a0, comm = 0x8dca03b8, sendmsg = 0x8f738000, recvmsg = 0x8f73cc00
I/TZ_init: (  804): TZ_init: sending initialization request...
I/TZ: client_server_communication(  804): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  804): Calling Communicate()
I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/TZ_init: (  804): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  804): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  804): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  804): Calling Communicate()
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,D/Finsky  ( 6689): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6689): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6689): [1] 5.onFinished: Scheduling replication attempt 2.
,I/TZ_COMMON: tlc_key_db_util: (  804): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: (  804): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  804): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  804): Calling Communicate()
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,I/TLC_TZ_CCM: register for default cert: (  804): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  804): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: (  804): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  804): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  804): Calling Communicate()
I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1075): COMM
,I/TZ: client_server_communication(  804): Client_Server_Close was called
,I/TZ_CCM_SERVER( 1075): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1075): CLOSESWCONN
D/QSEECOMAPI: ( 1075): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1075): QSEECom_shutdown_app, app_id = 2
,I/TZ: client_server_communication(  804): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 7537): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7537): TIMA service call for password change success!!
,D/UMC:AdminManager( 7537): init - start
,D/UMC:AdminManager( 7537): loadAdmins
,I/jxcore-log( 7448): Toggling radios to true
I/jxcore-log( 7448): 
,D/BluetoothAdapter( 7448): enable()
,D/BluetoothAdapter( 7448): enable(): BT is already enabled..!
,D/UMC:AdminManager( 7537): startPolicyHandlers
,I/UMC:TestPolicyHandler( 7537): Setup is called in testpolicyhandler
,D/WifiService(  804): New client listening to asynchronous messages
,D/UMC:AdminManager( 7537): init - end
,I/WifiManager( 7448): packageName : com.test.thalitest
V/UMC:AlarmHandler( 7537): Enter loadList
,D/SecContentProvider(  804): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  804): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  804): mCursor = null
,D/WifiService(  804): setWifiEnabled: true pid=7448, uid=10200
,E/WifiService(  804): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  804): Permission Denial: getCurrentUser() from pid=7448, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/WifiService(  804): Failed getting userId using ActivityManagerNative
W/WifiService(  804): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7448, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  804): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  804): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  804): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  804): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  804): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  804): name = wifi_on
,I/WifiService(  804): disconnect: pid=7448, uid=10200
,I/jxcore-log( 7448): Radios toggled
I/jxcore-log( 7448): 
I/wpa_supplicant( 1309): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7448): My device name is: samsung-SM-G900F
I/jxcore-log( 7448): 
,D/GSLBManager( 7537): migrateStoredUrlFromOldPref
,I/wpa_supplicant( 1309): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1309): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1309): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1309): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/GSLBManager( 7537): migrateStoredUrlFromOldPref : Migration Not Needed
E/WifiStateMachine(  804): WifiStateMachine: Leaving Connected state
D/UMC:UMCAdmin( 7537): deactivateUMCAdminIfNotRequired : -1
,I/wpa_supplicant( 1309): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1309): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1309): Disconnected - do not scan
I/wpa_supplicant( 1309): wlan0: State: DISCONNECTED -> DISCONNECTED
E/UMC:Utils( 7537): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7537): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7537): isContainer : 0
,E/WifiStateMachine(  804): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  804): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  804): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  804): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TaskPersister(  804): removeObsoleteFile: deleting file=17_task_thumbnail.png
W/LicenseLogService(  804): log() failed
,D/EnterpriseDeviceManagerService(  804): isManagedProfileUser(): userId = 0
,E/WifiStateMachine(  804): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/UMC:UMCAdmin( 7537): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7537): isContainer : 0
D/WifiP2pService(  804): InactiveState{ what=143375 }
,D/WifiP2pService(  804): P2pEnabledState{ what=143375 }
,D/UMC:UMCAdmin( 7537): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7537): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/ActivityManager(  804): Killing 6603:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,V/NativeCrypto( 1693): Read error: ssl=0xaf03fe00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1693): SSL shutdown failed: ssl=0xaf03fe00: I/O error during system call, Broken pipe
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): Forcing reevaluation
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): EvaluatingState{ when=-4ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): Validated
D/ConnectivityService(  804): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  804): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  804):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  804):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  804): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  804): calling update connectivity
,D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/QuickStartReceiver( 7537): Msg Id : 2
,D/QuickStartReceiver( 7537): model : SM-G900F
D/QuickStartReceiver( 7537): id : 100
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
,E/WifiStateMachine(  804): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore(  804): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService(  804): updateNetworkInfo()
,D/ConnectivityService(  804): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  804): updateNetworkInfo()
D/ConnectivityService(  804): ignoring duplicate network state non-change
D/ConnectivityService(  804): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
I/WifiTrafficPoller(  804): evaluateTrafficStatsPolling
,I/CLocInfoService(  804): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/Hs20UtilService( 1292): Starting #6
,I/Hs20UtilService( 1292): Message received 5007
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1292): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/WifiStateMachine(  804): Start Disconnecting Watchdog 1
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/wpa_supplicant( 1309): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1309): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1309): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1309): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1309): First Scan Start
,I/NearbySettings( 1292): DMSUtil.isNetworkConnected - P2P: IDLE
,I/wpa_supplicant( 1309): Scan requested (ret=0) - scan timeout 30 seconds
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
E/WifiStateMachine(  804): ConnectModeState: Network connection lost 
I/NearbySettings( 1292): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1292): MountReceiver.mPrefHandler - 7002
,E/WifiStateMachine(  804): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  804): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  804): InactiveState{ what=143375 }
,D/WifiP2pService(  804): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/AlarmManager(  804): waitForAlarm result :4
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  804): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  804): calling update connectivity
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  804): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  804): Not allowed due to - mEnabled false
D/Nat464Xlat(  804): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
E/WifiStateMachine(  804): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  804): updateConfiguredNetworkExpiration - currTime: 1453415979443
D/WifiStateMachine(  804): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): Disconnected - quitting
E/WifiStateMachine(  804): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  804): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/WifiTrafficPoller(  804): evaluateTrafficStatsPolling
,E/WifiStateMachine(  804): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  804): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/CLocInfoService(  804): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  804): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  804): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CSLegacyTypeTracker(  804): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  804): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,E/WifiStateMachine(  804): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  804): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  804): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/TelephonyNetworkFactory( 1472): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  804): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  804): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  804): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  804): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  804): uri = 20 selection = getPromptCredentialsEnabled
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecContentProvider2(  804): mCursor = null
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  804): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  804): updateIfacesLocked()
,V/NetworkStats(  804): performPollLocked(flags=0x1)
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  804): UpdateStatsForKnox
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  804): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
,D/SmartBondingService(  804): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,V/NetworkStats(  804): performPollLocked() took 6ms
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
,D/NtpTrustedTime(  804): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
V/NetworkStats(  804): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,W/libprocessgroup(  804): failed to open /acct/uid_1000/pid_6603/cgroup.procs: No such file or directory
,I/Hs20UtilService( 1292): Starting #7
I/Hs20UtilService( 1292): Message received 5007
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
,D/SecContentProvider2(  804): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  804): mCursor = null
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1292): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1292): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1292): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1472): FileWriteThread : threadType = 3
,V/AlarmManager(  804): waitForAlarm result :4
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,V/AlarmManager(  804): waitForAlarm result :4
,D/ConnectivityService(  804): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  804): updateDataUsageMap
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  804): MasterInitialState.processMessage what=3
,D/SmartBondingService(  804): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  804): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
,D/SmartBondingService(  804): getSBEnabled() enabled =false
I/CLocInfoService(  804): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  804): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  804): CLoinfo wifi false
,I/SystemBroadcastReceiver( 7205): [#DCM#] [DCM_Performance] onReceive completed in time  256 microsec. 
,D/accuweather( 2225): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5370): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3822): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3822): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 7205): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7205): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7205): [#DCM#] setIsConnectedForExtractors 
W/SLocation(  804): No Active Data Connection
,I/PCWCLIENTTRACE_PushUtil( 6818): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6818): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6818): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6818): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6818): noConnectivity : true
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7607): MountEmulatedStorage()
E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 10002
I/libpersona( 7607): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7607 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
,D/ActivityThread( 7607): Added TimaKeyStore provider
,D/ResourcesManager( 7607): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  804): Killing 6647:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7625): MountEmulatedStorage()
E/Zygote  ( 7625): v2
I/libpersona( 7625): KNOX_SDCARD checking this for 1000
I/libpersona( 7625): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7625 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SELinux ( 7625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7625): TimaSignature is unavailable
,D/ActivityThread( 7625): Added TimaKeyStore provider
,D/ResourcesManager( 7625): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  804): failed to open /acct/uid_1000/pid_6647/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7625): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7625): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/DIAGMON_AGENT( 7625): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7625): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7644): MountEmulatedStorage()
E/Zygote  ( 7644): v2
I/libpersona( 7644): KNOX_SDCARD checking this for 10011
I/libpersona( 7644): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7644 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1309): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1309): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1309): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1309): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1309): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  804): [1,453,415,980,493 ms] noteScanEnd no scan source
,I/SELinux ( 7644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7644): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/AlarmManager(  804): waitForAlarm result :4
,E/WifiStateMachine(  804): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@33caa731 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  804): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  804): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  804): setDetailed state send new extra info0x
,D/SecContentProvider2(  804): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  804): mCursor = null
,I/CLocInfoService(  804): External Intent Received android.net.wifi.SCAN_RESULTS
,D/TimaKeyStoreProvider( 7644): TimaSignature is unavailable
,D/ActivityThread( 7644): Added TimaKeyStore provider
,D/ResourcesManager( 7644): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/wpa_supplicant( 1309): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1309): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine(  804): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  804): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 1309): Associated with C0.AA.48
,D/SecContentProvider2(  804): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  804): mCursor = null
,I/ActivityManager(  804): Killing 6781:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/wpa_supplicant( 1309): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1309): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  804): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  804): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  804): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  804): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  804): mCursor = null
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/wpa_supplicant( 1309): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1309): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1309): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  804): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  804): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1309): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1309): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1309): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1309): Blacklist: Clear (temp) 
I/wpa_supplicant( 1309): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  804): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  804): mCursor = null
,E/WifiStateMachine(  804): Network connection established
,D/WifiNative-HAL(  804): callSECApiVoid - ID [50]
,E/WifiStateMachine(  804): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  804): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  804): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  804): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  804): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  804): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  804): Got NetworkAgent Messenger
E/ConnectivityService(  804): updateNetworkInfo()
D/ConnectivityService(  804): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  804): NetworkAgent connected
E/WifiStateMachine(  804): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  804): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client( 7644): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7644): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  804): failed to open /acct/uid_10015/pid_6781/cgroup.procs: No such file or directory
,E/WifiStateMachine(  804): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  804): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  804): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  804): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ActivityManager(  804): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7660 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/CommandListener(  279): Setting iface cfg
,E/Zygote  ( 7660): MountEmulatedStorage()
E/Zygote  ( 7660): v2
,I/libpersona( 7660): KNOX_SDCARD checking this for 10019
I/libpersona( 7660): KNOX_SDCARD not a persona
E/WifiStateMachine(  804): Start Dhcp Watchdog 2
I/ActivityManager(  804): Killing 6800:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  804): calculateWifiScore() report new score 60
I/WifiStateMachine(  804): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  804): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,D/ConnectivityService(  804): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  804): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  804): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityService(  804): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/SELinux ( 7660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7660): TimaSignature is unavailable
,D/ActivityThread( 7660): Added TimaKeyStore provider
,D/ResourcesManager( 7660): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7660): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7660): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453415980720
,I/KLMS-2.4.503: ( 7660): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,W/libprocessgroup(  804): failed to open /acct/uid_10016/pid_6800/cgroup.procs: No such file or directory
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7660): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7660): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  804): Killing 6555:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  804): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  804): do suspend false
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/SecContentProvider2(  804): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  804): mCursor = null
,D/WifiP2pService(  804): InactiveState{ what=143375 }
,D/WifiP2pService(  804): P2pEnabledState{ what=143375 }
,E/Zygote  ( 7680): MountEmulatedStorage()
E/Zygote  ( 7680): v2
I/libpersona( 7680): KNOX_SDCARD checking this for 10037
I/libpersona( 7680): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7680 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7680): TimaSignature is unavailable
,D/ActivityThread( 7680): Added TimaKeyStore provider
,D/ResourcesManager( 7680): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7680): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  804): failed to open /acct/uid_10034/pid_6555/cgroup.procs: No such file or directory
,E/SPPClientService( 5150): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6853): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6853): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6853): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6853): [SLFUCHKMGR] constructor called
,I/SA      ( 6853): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6853): [OR] == isSIMCardReady false ==
I/SA      ( 6853): [SCU] == networkStateCheck == false
,I/SA      ( 6853): [OR] onReceive END
,E/SPPClientService( 5150): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7697): MountEmulatedStorage()
E/Zygote  ( 7697): v2
I/libpersona( 7697): KNOX_SDCARD checking this for 10071
I/libpersona( 7697): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7697 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  804): Killing 4622:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
I/SELinux ( 7697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/TimaKeyStoreProvider( 7697): TimaSignature is unavailable
,D/ActivityThread( 7697): Added TimaKeyStore provider
,D/ResourcesManager( 7697): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7697): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7697): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7697): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/dhcpcd  ( 7715): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7715): version 5.5.6 starting
,E/dhcpcd  ( 7715): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/libprocessgroup(  804): failed to open /acct/uid_10035/pid_4622/cgroup.procs: No such file or directory
,D/comsamsunglog( 7697): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7697): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7697): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7697): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7697): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7697): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7697): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7697): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  804): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  804): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  804): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  804): selectionArgs: false
D/SettingsProvider(  804): selectionArgs: 10071
D/SecContentProvider(  804): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  804): ret = -1
,I/dhcpcd  ( 7715): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7715): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7715): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7715): bssid match
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/dhcpcd  ( 7715): wlan0: rebinding lease of 192.168.1.135
,E/SMD     (  287): DCD ON
,D/accuweather( 7697): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7697): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7697): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7697): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7697): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7697): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7697): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7697): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1324): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7697): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7697): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7729): MountEmulatedStorage()
E/Zygote  ( 7729): v2
I/libpersona( 7729): KNOX_SDCARD checking this for 1000
I/libpersona( 7729): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7729 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  804): Killing 6091:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/dhcpcd  ( 7715): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/SELinux ( 7729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7715): wlan0: leased 192.168.1.135 for 86400 seconds
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/WifiStateMachine(  804): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  804): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  804): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/TimaKeyStoreProvider( 7729): TimaSignature is unavailable
,D/ActivityThread( 7729): Added TimaKeyStore provider
,D/ResourcesManager( 7729): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7729): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  804): failed to open /acct/uid_10042/pid_6091/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7729): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7729): premStatus:2
,I/KnoxUsageLogPro( 7729): isEulaShown : false
I/KnoxUsageLogPro( 7729): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7755): MountEmulatedStorage()
E/Zygote  ( 7755): v2
I/libpersona( 7755): KNOX_SDCARD checking this for 10088
I/libpersona( 7755): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7755 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  804): Killing 5718:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/CountryDetector(  804): No listener is left
,E/SELinux ( 7755): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7755): TimaSignature is unavailable
,D/ActivityThread( 7755): Added TimaKeyStore provider
,D/ResourcesManager( 7755): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
W/libprocessgroup(  804): failed to open /acct/uid_10050/pid_5718/cgroup.procs: No such file or directory
,E/WifiStateMachine(  804): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  804): InactiveState{ what=143375 }
D/WifiP2pService(  804): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  804): WifiStateMachine DHCP successful
,E/WifiStateMachine(  804): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  804): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/ConnectivityService(  804): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  804): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/WifiStateMachine(  804): Not connected state, yet.
E/WifiStateMachine(  804): VerifyingLinkState enter
,D/WifiStateMachine(  804): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  804): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  804): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
,D/WifiNative-HAL(  804): callSECApiInt - ID [210]
,E/WifiStateMachine(  804): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  804): updateNetworkInfo()
,D/ConnectivityService(  804): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  804): Adding iface wlan0 to network 503
,I/CLocInfoService(  804): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine(  804): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  804): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  804): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  804): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  804): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  804): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  804): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  804): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  804): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  804): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  804): updateSourceRoutes : add src route for:192.168.1.135
E/WifiStateMachine(  804): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  804): Now, connected state.
E/WifiStateMachine(  804): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,V/        (  279): QcRouteController
E/WifiStateMachine(  804): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  804): evaluateTrafficStatsPolling
,I/CLocInfoService(  804): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/        (  279): QcRouteController
,E/WifiStateMachine(  804): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  804): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  804): mBoosterFLAG : 0
I/WifiTrafficPoller(  804): current booster mode : FullMode
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/WifiNative-HAL(  804): callSECApiVoid - ID [212]
E/WifiStateMachine(  804): ConnectedState Enter  mScreenOn=true scanperiod=20000
,V/        (  279): QcRouteController
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,I/CLocInfoService(  804): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  804): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ActivityManager(  804): Killing 6877:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,V/        (  279): QcRouteController
,D/Headlines( 5498): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5498): getCountryCode(): countryCode = DE
,D/Headlines( 5498): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5498): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5498): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5498): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,V/        (  279): QcRouteController
,E/Zygote  ( 7796): MountEmulatedStorage()
E/Zygote  ( 7796): v2
I/libpersona( 7796): KNOX_SDCARD checking this for 10128
I/libpersona( 7796): KNOX_SDCARD not a persona
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ActivityManager(  804): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7796 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/        (  279): QcRouteController
,V/        (  279): QcRouteController
,I/SELinux ( 7796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7796): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/        (  279): QcRouteController
,D/TimaKeyStoreProvider( 7796): TimaSignature is unavailable
,D/ActivityThread( 7796): Added TimaKeyStore provider
,D/ConnectivityService(  804): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  804): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  804): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  804): updateNetworkInfo()
D/ConnectivityService(  804): calling update connectivity
E/ConnectivityService(  804): updateNetworkInfo()
D/ConnectivityService(  804): ignoring duplicate network state non-change
D/ConnectivityService(  804): ignoring duplicate network state non-change
D/ConnectivityService(  804): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  804): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  804): calling update connectivity
,D/ConnectivityService(  804): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  804):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  804):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  804): currentScore = 0, newScore = 60
D/ConnectivityService(  804):    accepting network in place of null
D/ConnectivityService(  804): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  804): Validated
,D/TelephonyNetworkFactory( 1472): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  804): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  804): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  804): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  804): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  804): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,W/libprocessgroup(  804): failed to open /acct/uid_10051/pid_6877/cgroup.procs: No such file or directory
,D/ConnectivityService(  804): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  804): calling update connectivity
,D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  804): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  804): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  804):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  804):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  804): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  804): calling update connectivity
,D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  804): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/SmartBondingService(  804): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  804): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
,V/NetworkStats(  804): updateIfacesLocked()
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
V/NetworkStats(  804): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  804): UpdateStatsForKnox
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
,V/NetworkStats(  804): performPollLocked() took 3ms
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  804): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/NtpTrustedTime(  804): currentTimeMillis() cache hit
,D/NtpTrustedTime(  804): currentTimeMillis() cache hit
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
D/NtpTrustedTime(  804): currentTimeMillis() cache hit
V/NetworkStats(  804): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7796): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7796): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7796): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7796): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7796): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7796): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7796): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7796): Loading: webviewchromium
,I/LibraryLoader( 7796): Time to load native libraries: 4 ms (timestamps 1299-1303)
,I/LibraryLoader( 7796): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7796): Binding Chromium to main looper Looper (main, tid 1) {3e0d0852}
,I/LibraryLoader( 7796): Expected native library version number "",actual native library version number ""
,I/chromium( 7796): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/BrowserStartupController( 7796): Initializing chromium process, renderers=0
,W/art     ( 7796): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7796): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7796): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7796): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 7796): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7796): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7796): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7796): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7796): Remote Branch: 
I/Adreno-EGL( 7796): Local Patches: 
I/Adreno-EGL( 7796): Reconstruct Branch: 
,W/AudioManagerAndroid( 7796): Requires BLUETOOTH permission
,I/NSApplication( 7796): Starting up...
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService(  804): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
D/PowerManagerService(  804): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  804): lcd : 7 +
,E/Zygote  ( 7854): MountEmulatedStorage()
I/libpersona( 7854): KNOX_SDCARD checking this for 10138
E/Zygote  ( 7854): v2
I/libpersona( 7854): KNOX_SDCARD not a persona
,D/lights  (  804): lcd : 7 -
,I/ActivityManager(  804): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7854 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  804): Killing 6894:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,D/lights  (  804): lcd : 1 +
,D/lights  (  804): lcd : 1 -
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,I/art     (  313): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 301us total 15.963ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.823ms
,I/SELinux ( 7854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 376us total 7.976ms
,E/SELinux ( 7854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  804): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  804): MasterInitialState.processMessage what=3
,D/SmartBondingService(  804): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  804): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  804): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  804): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
,I/CLocInfoService(  804): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  804): CLocinfo wifi true 
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7854): TimaSignature is unavailable
D/SmartBondingService(  804): getNetworkEnabled : wifi : true mobile : true
,D/ActivityThread( 7854): Added TimaKeyStore provider
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2225): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  804): failed to open /acct/uid_10058/pid_6894/cgroup.procs: No such file or directory
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2107): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2107): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3822): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3822): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5370): type=WIFI subType= reason=null isConnected=true
,I/SystemBroadcastReceiver( 7205): [#DCM#] [DCM_Performance] onReceive completed in time  185 microsec. 
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7205): [#DCM#] Calling notifyListeners. 
I/DCMController( 7205): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7205): [#DCM#] setIsConnectedForExtractors 
,I/DatabaseRebuilderTask( 7205): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7205): [#DCM#] onCreate FrameworkService 
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/FrameworkService( 7205): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7205): [#DCM#] getSuccessState = true
I/FrameworkService( 7205): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7205): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7854): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  804): mCursor = null
,I/SystemUtils( 7205): [#DCM#] LM: false,AM:625590272
,I/DCMThreadPoolExecutor( 7205): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7205): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1d93ac66 is submitted
I/FrameworkService( 7205): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 25260 mirosec. 
,W/ResourcesManager( 7854): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7854): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/DatabaseRebuilderTask( 7205): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7205): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7205): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,W/ResourcesManager( 7854): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/DatabaseRebuilderTask( 7205): [#DCM#] topDocs hits = 0
,I/DatabaseRebuilderTask( 7205): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7205): [#DCM#] releaseLuceneReader done 
,I/DatabaseRebuilderTask( 7205): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7205): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7205): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7205): [#DCM#] afterExecute FutureTask
,I/DCMController( 7205): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1d93ac66
,D/QuickConnect( 7854): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7854): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7854): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7873): MountEmulatedStorage()
,E/Zygote  ( 7873): v2
I/libpersona( 7873): KNOX_SDCARD checking this for 10163
I/libpersona( 7873): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7873 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
I/ActivityManager(  804): Killing 6257:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7873): TimaSignature is unavailable
,D/ActivityThread( 7873): Added TimaKeyStore provider
,D/ResourcesManager( 7873): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7873): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7873): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7873): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7873): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  804): failed to open /acct/uid_1000/pid_6257/cgroup.procs: No such file or directory
,D/RCPManagerService(  804): exchangeData() failure , invalid userId
,D/RCPManagerService(  804): exchangeData() failure , invalid userId
,D/RCPManagerService(  804): exchangeData() failure , invalid userId
,D/RCPManagerService(  804): exchangeData() failure , invalid userId
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/Zygote  ( 7896): MountEmulatedStorage()
E/Zygote  ( 7896): v2
I/libpersona( 7896): KNOX_SDCARD checking this for 10078
I/libpersona( 7896): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7896 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,I/SELinux ( 7896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7896): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  804): exchangeData() failure , invalid userId
D/RCPManagerService(  804): exchangeData() failure , invalid userId
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7520): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7520): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7520): StateMachine : Current State = 1
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7520): StateMachine : Changed Current State = 1
,I/ActivityManager(  804): Killing 6915:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7896): TimaSignature is unavailable
,D/ActivityThread( 7896): Added TimaKeyStore provider
,I/ActivityManager(  804): Killing 6975:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): last run: 1453415898475 -- System.currentTimeMillis()-last_run: 83980
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip last_72_check
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/Zygote  ( 7912): MountEmulatedStorage()
,E/Zygote  ( 7912): v2
I/libpersona( 7912): KNOX_SDCARD checking this for 10178
I/libpersona( 7912): KNOX_SDCARD not a persona
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,I/ActivityManager(  804): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7912 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/SELinux ( 7912): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7912): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7912): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/ResourcesManager( 7896): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,D/ConnectivityService(  804): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/TimaKeyStoreProvider( 7912): TimaSignature is unavailable
,D/ActivityThread( 7912): Added TimaKeyStore provider
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png,
D/BadgeProvider( 7896): onCreate
D/BadgeProvider( 7896): DatabaseHelper
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/ResourcesManager( 7912): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/BadgeProvider( 7896): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7896): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7896): sendNotify, [notify] : null
D/BadgeProvider( 7896): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7896): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7896): update, [UpdateCount] : 1
,D/Launcher.Model( 1486): reloadBadges entered.
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
W/libprocessgroup(  804): failed to open /acct/uid_10098/pid_6915/cgroup.procs: No such file or directory
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,W/libprocessgroup(  804): failed to open /acct/uid_10033/pid_6975/cgroup.procs: No such file or directory
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,I/ActivityManager(  804): Killing 6953:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7873): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2458): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2458): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  804): failed to open /acct/uid_10099/pid_6953/cgroup.procs: No such file or directory
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,D/WaitQueueForNetworkActivate( 7182): notifyNetworkActivated
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
,D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2458): [AccountUtils] Account not ready
W/Kids    ( 2458): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2458): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2458): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2458): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2458): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2458): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2458): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2458): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,W/ContextImpl( 7182): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  804): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager(  804): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/WifiStateMachine(  804): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  804): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  804): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  804): identical MTU - not setting
,D/ConnectivityService(  804): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  804): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
E/WifiStateMachine(  804): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
V/        (  279): QcRouteController
,D/SmartBondingService(  804): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  804): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
D/SmartBondingService(  804): getSBEnabled() enabled =false
,V/        (  279): QcRouteController
,W/NetworkManagementService(  804): route cmd failed: 
W/NetworkManagementService(  804): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  804): '
W/NetworkManagementService(  804): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  804): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  804): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  804): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  804): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  804): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  804): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  804): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  804): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  804): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  804): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  804): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  804): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  804): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  804): calling update connectivity
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  804): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,D/ConnectivityService(  804): calling update connectivity
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  804):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  804): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7182): AutoUpdateManager:IDLE:execute
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,I/Hs20UtilService( 1292): Starting #8
,I/Hs20UtilService( 1292): Message received 5007
D/InitializeManagerStateMachine( 7182): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7182): exit::IDLE
D/InitializeManagerStateMachine( 7182): entry::NETWORK_CHECK
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/NearbySettings( 1292): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 7182): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7182): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7182): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7182): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7182): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7182): entry::SUCCESS
D/hcjo    ( 7182): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1292): Starting #9
,I/Hs20UtilService( 1292): Message received 5007
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
D/hcjo    ( 7182): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7182): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7182): exit::SUCCESS
D/InitializeManagerStateMachine( 7182): entry::IDLE
,I/Hs20UtilService( 1292): Starting #10
,I/Hs20UtilService( 1292): Message received 5007
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1292): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1292): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,I/Hs20UtilService( 1292): Starting #11
,I/Hs20UtilService( 1292): Message received 5007
,D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1292): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  804): callSECApi what=220
D/WifiStateMachine(  804): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6818): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6818): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6818): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6818): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7625): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  804): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=804
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
D/PowerManagerService(  804): [s] DisplayPowerCallbacks : onStateChanged()
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  804): lcd : 8 +
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/lights  (  804): lcd : 8 -
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
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
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7644): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7644): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7644): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7660): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7660): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453415983016
,I/KLMS-2.4.503: ( 7660): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7660): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7660): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7660): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7660): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SO_AGENT( 7680): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/GCM     ( 1693): Connected
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1693): Message class com.google.f.a.a.p
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/SPPClientService( 5150): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6853): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6853): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6853): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6853): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6853): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6853): [SCU] == networkStateCheck == true
,I/SA      ( 6853): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6853): isChinaCountryCode : false
I/SA      ( 6853): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6853): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 6853): [OR] GetMyCountryZoneTask
,I/SA      ( 6853): [OR] onReceive END
,I/SA      ( 6853): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6853): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 6853): [SSP] query invoked
,D/accuweather( 7697): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7697): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/art     (  804): Explicit concurrent mark sweep GC freed 71841(4MB) AllocSpace objects, 8(193KB) LOS objects, 29% free, 38MB/54MB, paused 1.396ms total 98.671ms
,I/KnoxUsageLogPro( 7729): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7729): premStatus:2
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
I/SA      ( 6853): [TPMU] GetMccFromDB : null
I/SA      ( 6853): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6853): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7729): isEulaShown : false
I/KnoxUsageLogPro( 7729): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/Headlines( 5498): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5498): getCountryCode(): countryCode = DE
,D/Headlines( 5498): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5498): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5498): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5498): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5498): requestUpdateNewsWelcomeCard !!! no welcome card
,E/File    ( 6853): fail readDirectory() errno=2
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7854): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7854): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7854): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  804): exchangeData() failure , invalid userId
,D/RCPManagerService(  804): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7520): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7520): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7520): StateMachine : Current State = 1
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7520): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): last run: 1453415898475 -- System.currentTimeMillis()-last_run: 84842
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5625): ... skip last_72_check
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4253, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  804): Plugged
I/MotionRecognitionService(  804): setPowerConnected  = true
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2458): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2458): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7182): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7182): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7182): exit::IDLE
D/InitializeManagerStateMachine( 7182): entry::NETWORK_CHECK
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InitializeManagerStateMachine( 7182): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7182): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7182): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7182): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7182): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7182): entry::SUCCESS
D/hcjo    ( 7182): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7182): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7182): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7182): exit::SUCCESS
D/InitializeManagerStateMachine( 7182): entry::IDLE
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
,D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/Kids    ( 2458): [AccountUtils] Account not ready
W/Kids    ( 2458): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2458): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2458): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2458): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2458): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2458): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2458): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2458): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2458): 	at java.lang.Thread.run(Thread.java:818)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
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
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7448): 
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SA      ( 6853): [RC New] Execute method=[GET] start
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SA      ( 6853): [RC New] Security=[true]
,I/System.out( 6853): Thread-1115(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6853): Thread-1115(ApacheHTTPLog):isShipBuild true
,I/System.out( 6853): Thread-1115(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/Watchdog(  804): !@Sync 3
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7448): 
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SA      ( 6853): [RC New] [v2liruge] api execute + 644
,I/SA      ( 6853): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6853): AsyncTask #1 calls detatch()
,I/SA      ( 6853): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6853): [OCP] update openData : PL
,I/SA      ( 6853): [TPMU] getNetworkMcc : 
,I/SA      ( 6853): [SCU] saveMccToPreferece Start
,I/SA      ( 6853): [SCU] RegionMCC : 260
I/SA      ( 6853): [SSP] query invoked
,I/SA      ( 6853): [TPMU] GetMccFromDB : null
,I/SA      ( 6853): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6853): [SCU] saveMccToPreferece End
,I/SA      ( 6853): [RC New] executeRequest [v2liruge] end. 697
I/SA      ( 6853): [RC New] Execute end
I/SA      ( 6853): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6853): [OR] GetMyCountryZoneTask Success
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  804): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  804): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/jxcore-log( 7448): Test app app.js loaded
I/jxcore-log( 7448): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7448): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7448): BLE advertisement is supported
I/jxcore-log( 7448): 
,I/chromium( 7448): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7715): wlan0: sending IPv6 Router Solicitation
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  804): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 804) eventTime = 105942
,D/PowerManagerService(  804): [s] UserActivityState : 2 -> 1
,D/PowerManagerService(  804): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=804 (0x0)
D/PowerManagerService(  804): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=804, ws=WorkSource{10059}) (elapsedTime=3502)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
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
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/GAV4    ( 7796): Thread[GAThread,5,main]: No campaign data found.
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6818): mConnectivityHandler : connected
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6818): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6818): ================================================
,I/CSTORAGE( 6818):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6818): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6818): [GetString-S]
,E/art     ( 6818): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6818): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6818): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6818): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6818): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6818): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6818): [ensureRegistration] - No Samsung account
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6,
,I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  804): SIOP:: AP = 410, PST = 433, CUR = 300
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7715): wlan0: sending IPv6 Router Solicitation
,D/PackageManager(  804): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  804): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/InputReader(  804): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  ( 7970): MountEmulatedStorage()
I/ActivityManager(  804): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7970 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 7970): v2
I/libpersona( 7970): KNOX_SDCARD checking this for 10034
,I/libpersona( 7970): KNOX_SDCARD not a persona
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/SELinux ( 7970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Books/Books.apk
,D/RegisteredServicesCache( 1466): empty dynamic service
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TimaKeyStoreProvider( 7970): TimaSignature is unavailable
,D/ActivityThread( 7970): Added TimaKeyStore provider
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  804): mCursor = null
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/FeatureConfig( 7970): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  804): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  804): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  804): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  804): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/Zygote  ( 7999): MountEmulatedStorage()
E/Zygote  ( 7999): v2
I/libpersona( 7999): KNOX_SDCARD checking this for 10035
I/libpersona( 7999): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7999 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  804): Killing 7016:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7999): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7999): TimaSignature is unavailable
,D/ActivityThread( 7999): Added TimaKeyStore provider
,D/ResourcesManager( 7999): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/libprocessgroup(  804): failed to open /acct/uid_10020/pid_7016/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD ON
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): checkState()
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8023): MountEmulatedStorage()
,E/Zygote  ( 8023): v2
I/libpersona( 8023): KNOX_SDCARD checking this for 10017
I/libpersona( 8023): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=8023 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,I/SELinux ( 8023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8023): TimaSignature is unavailable
,D/ActivityThread( 8023): Added TimaKeyStore provider
,D/ResourcesManager( 8023): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7999): getConnectedDevices
,D/-----SIC-----( 7999): ------------------skip uv
,D/-----SIC-----( 7999): ------------------skip SPO2
,D/-----SIC-----( 7999): ------------------skip TGH
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,I/SecureStorage( 8023): [INFO]: SPID(0x00000000)Processing data
,W/ContextImpl( 7999): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7999): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,I/SecureStorage(  344): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 8023
I/SecureStorage(  344): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,V/MediaPlayer( 7999): decode(34, 19359868, 4230)
,V/MediaPlayerService(  292): decode(30, 19359868, 4230)
,V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
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
V/StagefrightPlayer(  292): setDataSource(30, 19359868, 4230)
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
,V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
,I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0824ab0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
,V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0824ab0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthServiceInstalled() : HealthService is Installed.
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
,V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/ActivityManager(  804): Killing 7025:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
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
I/SecMediaClock(  292): SecMediaClock destructor
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
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7999): decode(33, 19213040, 15440)
,V/MediaPlayerService(  292): decode(30, 19213040, 15440)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
,V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 8, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
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
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 1, 0, 0)
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
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/ActivityManager(  804): Killing 7046:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  292): wait for playback complete
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
,D/AdaptiveEventManager( 1169): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1169): M updateContainers()
D/AdaptiveEventContainerSmall( 1169): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1169): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1169): pedoEvent == null
I/UpdateIcingCorporaServi( 1573): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8071): MountEmulatedStorage()
E/Zygote  ( 8071): v2
I/libpersona( 8071): KNOX_SDCARD checking this for 10075
I/libpersona( 8071): KNOX_SDCARD not a persona
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/ActivityManager(  804): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=8071 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
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
V/MediaPlayer( 7999): decode(36, 19257568, 9226)
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SELinux ( 8071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  292): decode(30, 19257568, 9226)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,I/SELinux ( 8071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
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
V/StagefrightPlayer(  292): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
E/SELinux ( 8071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
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
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  292): notify(0xb03fc290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 1, 0, 0)
,V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
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
,E/DatabaseUtils(  804): Writing exception to parcel
E/DatabaseUtils(  804): java.lang.NullPointerException: key == null
E/DatabaseUtils(  804): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  804): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  804): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  804): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  804): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  804): 	at android.os.Binder.execTransact(Binder.java:446)
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
,D/TimaKeyStoreProvider( 8071): TimaSignature is unavailable
,D/ActivityThread( 8071): Added TimaKeyStore provider
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 8, 0, 0)
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
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7999): decode(37, 19364180, 4890)
,V/MediaPlayerService(  292): decode(30, 19364180, 4890)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
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
,V/AudioCache(  292): notify(0xaf017240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
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
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
,V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 1, 0, 0)
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
V/AudioCache(  292): notify(0xaf017240, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,I/UpdateIcingCorporaServi( 1573): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,D/ResourcesManager( 8071): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7999): decode(38, 19290344, 17329)
V/MediaPlayerService(  292): decode(30, 19290344, 17329)
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
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
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
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,D/FileShare-Server( 8071): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
,I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7999): decode(39, 19190536, 6644)
V/MediaPlayerService(  292): decode(30, 19190536, 6644)
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
V/MediaPlayerService(  292): player type = 3
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer(  292): setDefault
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
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
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
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
,V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
,V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 1, 0, 0)
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
V/AudioCache(  292): notify(0xb0824ab0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,E/Zygote  ( 8104): MountEmulatedStorage()
E/Zygote  ( 8104): v2
I/libpersona( 8104): KNOX_SDCARD checking this for 1000
I/libpersona( 8104): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8104 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  804): Killing 7068:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
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
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/MediaPlayer( 7999): decode(40, 19266876, 23389)
,V/MediaPlayerService(  292): decode(30, 19266876, 23389)
I/SELinux ( 8104): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
I/SELinux ( 8104): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/libprocessgroup(  804): failed to open /acct/uid_10003/pid_7025/cgroup.procs: No such file or directory
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
W/libprocessgroup(  804): failed to open /acct/uid_1000/pid_7046/cgroup.procs: No such file or directory
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
E/SELinux ( 8104): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
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
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
,I/SecMediaClock(  292): SecMediaClock constructor
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
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 1, 0, 0)
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
V/AudioCache(  292): notify(0xaf017330, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/TimaKeyStoreProvider( 8104): TimaSignature is unavailable
,D/ActivityThread( 8104): Added TimaKeyStore provider
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): addBatteryData
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7999): decode(32, 19156232, 8154)
V/MediaPlayerService(  292): decode(30, 19156232, 8154)
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
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
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
,V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
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
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 1, 0, 0)
V/AudioCache(  292): prepared
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
,W/libprocessgroup(  804): failed to open /acct/uid_10112/pid_7068/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
,I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
D/ResourcesManager( 8104): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0),
,V/AwesomePlayer(  292): onCheckAudioStatus
,V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb03fc290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
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
V/MediaPlayer( 7999): decode(42, 19129712, 4804)
V/MediaPlayerService(  292): decode(30, 19129712, 4804)
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
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
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
,I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 5, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(1)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaf017240, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaf017240, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
,I/AudioPlayer(  292): reset out
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
,V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7999): decode(43, 19099164, 9400)
,V/MediaPlayerService(  292): decode(30, 19099164, 9400)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/MediaPlayer( 7999): decode(50, 19172584, 4112)
V/MediaPlayerService(  292): decode(32, 19172584, 4112)
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
,V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
,V/AudioCache(  292): ignored
V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
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
V/StagefrightPlayer(  292): setDataSource(32, 19172584, 4112)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(33) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(34) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
,I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
,I/SecMediaClock(  292): SecMediaClock constructor
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
I/SecMediaClock(  292): reset
V/AwesomePlayer(  292): current audio track index (0) is added to vector
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
V/AwesomePlayer(  292): initAudioDecoder
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/AwesomePlayer(  292): checkOffloadExceptions is true
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
,I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
,I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0824ab0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 200, 973, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
D/ShortcutReceiver( 8104):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/AudioPlayer(  292): Audio channels(1)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  292): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,I/AudioPlayer(  292): First fillBuffer call!!
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0824ab0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
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
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
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
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7999): decode(44, 19307764, 52024)
V/MediaPlayerService(  292): decode(30, 19307764, 52024)
V/MediaPlayerService(  292): player type = 3
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
V/StagefrightPlayer(  292): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
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
V/AudioPolicyManager(  292): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 1, 0, 0)
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
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/ActivityManager(  804): Killing 7087:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
I/AudioPlayer(  292): First fillBuffer call!!
D/PackageBroadcastService( 2458): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
I/PeopleContactsSync( 2458): CP2 sync disabled
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,W/libprocessgroup(  804): failed to open /acct/uid_10118/pid_7087/cgroup.procs: No such file or directory
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
,V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): addBatteryData
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017330, 8, 0, 0)
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
,V/MediaPlayer( 7999): decode(45, 19172584, 4112)
V/MediaPlayerService(  292): decode(30, 19172584, 4112)
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
,V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19172584, 4112)
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  292): mBitrate = -1 bits/sec
I/OggExtractor(  292): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  292): current audio track index (0) is added to vector
V/AwesomePlayer(  292): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  292): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  292): prepare
V/AwesomePlayer(  292): prepareAsync
,V/MediaPlayerService(  292): wait for prepare
V/AwesomePlayer(  292): onPrepareAsyncEvent
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
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
,V/AwesomePlayer(  292): play
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
V/AudioCache(  292): notify(0xb03fc290, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
V/MediaPlayerService(  292): wait for playback complete
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  292): postAudioEOS delayUs (0)
V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb03fc290, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
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
,V/StagefrightPlayer(  292): reset
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
V/MediaPlayer( 7999): decode(46, 19235660, 21825)
V/MediaPlayerService(  292): decode(30, 19235660, 21825)
,V/MediaPlayerService(  292): player type = 3
V/AwesomePlayer(  292): setDefault
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
V/StagefrightPlayer(  292): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,D/Utils   (  292): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  292): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  292): mBitrate = -1 bits/sec
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
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
,V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xaf017240, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 1, 0, 0)
V/AudioCache(  292): prepared
V/AudioCache(  292): wait - success
V/MediaPlayerService(  292): start
V/StagefrightPlayer(  292): start
V/AwesomePlayer(  292): play
,V/AwesomePlayer(  292): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  292): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  292): start of Playback, useOffload 0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  292): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  292): Audio channels(2)
,I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 6, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): addBatteryData
,I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 7, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf017240, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
,I/OggExtractor(  292): ~OggExtractor ++
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
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
,V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7999): decode(47, 19134596, 21552)
V/MediaPlayerService(  292): decode(30, 19134596, 21552)
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
V/AwesomePlayer(  292): mSecMediaClock clear
V/StagefrightPlayer(  292): StagefrightPlayer
V/AwesomePlayer(  292): setListener
V/StagefrightPlayer(  292): initCheck
,V/AwesomePlayer(  292): setAudioSink
V/StagefrightPlayer(  292): setDataSource(30, 19134596, 21552)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
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
,V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
,V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
,V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 5, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 1, 0, 0)
V/AudioCache(  292): prepared
,V/AudioCache(  292): wait - success
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
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 6, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): addBatteryData
I/AudioPlayer(  292): First fillBuffer call!!
I/AudioPlayer(  292): >>> setAudioEffect Read mAudioFormat : 1, event : 4292761, value : -2137358184
E/AudioPlayer(  292): >>> setAudioEffect Error mAudioFormat : 1, event : 4292761, value : -2137358184
V/MediaPlayerService(  292): wait for playback complete
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  292): postAudioEOS delayUs (0)
,V/AwesomePlayer(  292): onCheckAudioStatus
V/AwesomePlayer(  292): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  292): onStreamDone
V/AwesomePlayer(  292): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  292): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  292): notify(0xb0824ab0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xb0824ab0, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
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
V/StagefrightPlayer(  292): reset
,V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
,V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
V/MediaPlayer( 7999): decode(48, 19228560, 7017)
V/MediaPlayerService(  292): decode(30, 19228560, 7017)
V/MediaPlayerService(  292): player type = 3
,V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): constructor
V/AwesomePlayer(  292): setDefault
V/AwesomePlayer(  292): reset_l()
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
V/StagefrightPlayer(  292): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
,V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
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
V/AwesomePlayer(  292): prepareAsync
V/MediaPlayerService(  292): wait for prepare
,V/AwesomePlayer(  292): onPrepareAsyncEvent
I/SecMediaClock(  292): SecMediaClock constructor
I/SecMediaClock(  292): reset
I/SecVideoCapture(  292): SecVideoCapture constructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): initAudioDecoder
V/AwesomePlayer(  292): checkOffloadExceptions is true
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  292): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  292): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  292): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  292): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  292): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  292): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  292): finishAsyncPrepare_l
V/AwesomePlayer(  292): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 200, 973, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 5, 0, 0)
V/AudioCache(  292): ignored
,V/AwesomePlayer(  292): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 1, 0, 0)
V/AudioCache(  292): prepared
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
I/AudioPlayer(  292): Audio channels(2)
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  292): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  292): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  292): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 6, 0, 0)
,V/AudioCache(  292): ignored
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
,V/AudioCache(  292): notify(0xaf9092e0, 2, 0, 0)
V/AudioCache(  292): playback complete - thread will wake up later
V/AwesomePlayer(  292): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 7, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  292): addBatteryData
V/AudioCache(  292): wait - success
,V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  292): notify(0xaf9092e0, 8, 0, 0)
V/AudioCache(  292): ignored
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
D/AudioPlayer(  292): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  292): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  292): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  292): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  292): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  292): ~OggSource --
I/OggExtractor(  292): ~OggExtractor ++
I/OggExtractor(  292): ~MyVorbisExtractor ++ 
,I/OggExtractor(  292): ~MyVorbisExtractor --
I/OggExtractor(  292): ~OggExtractor --
I/AudioPlayer(  292): reset out
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  292): SecVideoCapture destructor
I/SecVideoCapture(  292): reset
V/AwesomePlayer(  292): mSecCapture clear
I/SecMediaClock(  292): SecMediaClock destructor
V/AwesomePlayer(  292): mSecMediaClock clear
,V/StagefrightPlayer(  292): ~StagefrightPlayer
V/StagefrightPlayer(  292): reset
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,V/AwesomePlayer(  292): destructor
V/AwesomePlayer(  292): reset_l()
V/AwesomePlayer(  292): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  292): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  292): mAudioTrackVector clear
V/AwesomePlayer(  292): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  292): mSecCapture clear
V/AwesomePlayer(  292): mSecMediaClock clear
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SecureStorage(  344): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage(  344): [INFO]: SPID(0x00000005)PID: 8023, TID: 8035
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SecureStorage( 8023): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 8023): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7999): getWritableDatabase(pwd)
,I/SecSQLiteOpenHelper( 7999): getDatabaseLocked(b,b,pwd)...
,I/SecSQLiteOpenHelper( 7999): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7999): Android Version: 5.0
,D/SecSQLiteDatabase( 7999): Load library secsqlite.so for Android 5.0
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/SecSQLiteDatabase( 7999): openSecureDatabase...
,I/SecSQLiteDatabase( 7999): private openSecureDatabase...
,I/SecSQLiteConnectionPool( 7999): OpenSecure
I/SecSQLiteConnectionPool( 7999): OpenSecure with password
,I/SecSQLiteConnectionPool( 7999): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7999): ...private openSecureDatabase
,I/SecSQLiteDatabase( 7999): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 7999): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 7999): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthServiceInstalled() : HealthService is Installed.
,W/System.err( 7999): java.lang.NumberFormatException: Invalid int: "null"
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7999): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,W/System.err( 7999): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7999): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 7999): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7999): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7999): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7999): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7999): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/PreloadUpdateManagerStateMachine( 7182): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7182): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7182): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 7182): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7182): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7182): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7182): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7182): entry::IDLE
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/dhcpcd  ( 7715): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7715): wlan0: no IPv6 Routers available
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8,
,D/PreloadUpdateManagerStateMachine( 7182): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7182): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7182): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7182): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7182): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7182): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7182): entry::IDLE
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8,
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen,
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen,
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen,
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/GAV3    ( 7999): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/FactoryTest( 6523): Not factory mode
,D/FactoryTest( 6523): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6523): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6523): still no open session command from host, so toast
,W/ContextImpl( 6523): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6523): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6523): Timeline: Activity_launch_request id:com.android.settings time:116821
,E/PersonaManagerService(  804): inState():  stateMachine is null !!
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  804): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  804): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  804): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/MTPRx   ( 6523): started activity for popup
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 6523): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6523): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6523): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6523): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6523): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6523): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6523): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6523): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6523): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/InputMethodManagerService(  804): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  804): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@16183f71 attribute=null, token = android.os.BinderProxy@cc64594
,E/ActivityManager(  804): Invalid thumbnail dimensions: 576x576
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6523): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6523): dev.kiessupport is : TRUE
,D/Activity( 6523): performCreate Call secproduct feature valuefalse
D/Activity( 6523): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  804): post active user change for 0
,D/KnoxTimeoutHandler(  804): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  804): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7448): Timeline: Activity_idle id: android.os.BinderProxy@14c6d51 time:117097
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ActivityManager(  804): Waited long enough for: ServiceRecord{3cc60a76 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,D/SSRM:m  (  804): SIOP:: AP = 390, PST = 425, CUR = 300
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,V/AlarmManager(  804): waitForAlarm result :4
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
I/MotionRecognitionService(  804): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6689): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6689): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6689): [1] 5.onFinished: Scheduling replication attempt 3.
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,V/AlarmManager(  804): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  804): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  804): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  804): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/CustomFrequencyManagerService(  804): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 804  tag : ACTIVITY_RESUME_BOOSTER@10
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  804): waitForAlarm result :4
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/SSRM:m  (  804): SIOP:: AP = 360, PST = 412, CUR = 300
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  804): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  804): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
D/lights  (  804): lcd : 1 +
,D/lights  (  804): lcd : 1 -
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  804): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  804): CMD_RSSI_POLL : out!
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/SMD     (  287): DCD ON
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/Watchdog(  804): !@Sync 4
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/DisplayPowerController(  804): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  804): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  804): Nap time (uid 1000)...
,I/PowerManagerService(  804): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  804): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  804): setDeviceInteractive: 0
,D/PowerManagerService(  804): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/InputManager-JNI(  804): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  804): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  804): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  804): handleSandman : startDream()
,E/PowerManagerService(  804): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  804): Sleeping (uid 1000)...
D/PowerManagerService(  804): [s] UserActivityState : 4 -> 0
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/PowerManagerService(  804): [input device light] setInputDeviceLightOn is called : 0
,D/InputManager-JNI(  804): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  804): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  804): [input device light] handleInputDeviceLightOff
D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/SContextService(  804): 	.unregisterCallback : 1, client=
D/SContextService(  804): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@efb81ac, Service = Auto Rotation, used = 1
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,W/CAE     (  804): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  804): stop(ContextProvider.java:149)
,V/CAE     (  804): clear(AutoRotationRunner.java:182)
,V/CAE     (  804): disable(AutoRotationRunner.java:171)
,I/CAE     (  804): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  804): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  299): sendContextData: -78, 7, 0, 0
,D/CAE     (  804): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  804): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  804): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  804): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  804): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  804): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  804): removeSContextService() : service = Auto Rotation
D/SContextService(  804): ===== SContext Service List =====
D/SContextManager(  804):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@56c0ad2, service=Auto Rotation
D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): timeout : 5000
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3560): getWritableDatabase(pwd)
,D/DisplayPowerController(  804): ColorFade: onAnimationStart
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 0
,D/lights  (  804): lcd : 0 +
,D/DisplayPowerController(  804): getFinalBrightness : 8 -> 0
,D/lights  (  804): lcd : 0 -
,I/SQLiteSecureOpenHelper( 3560): getDatabaseLocked(b,b,pwd)...
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
D/DisplayPowerController(  804): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/LightsService(  804): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 804) 
D/LightsService(  804): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  804): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  804): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  804): unregisterListener ::   
D/lights  (  804): led_pattern : 5 +
,D/BatteryService(  804): turn on LED for fully charged
,I/CAE     (  804): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  804): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  804): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  804): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  299): sendContextData: -76, 13, -46, 0
,D/lights  (  804): led_pattern : 5 -
,D/LightsService(  804): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  804): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 22, 40, 16,
,D/SensorHubManager(  804): SendSensorHubData: send data = -63, 14, 22, 40, 16
D/Sensorhubs(  299): sendContextData: -63, 14, 22, 40, 16
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  804):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  804): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  804): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  804): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  804): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  804): do suspend true
,D/NotificationService(  804): ACTION_SCREEN_OFF
D/LightsService(  804): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 804) 
D/LightsService(  804): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  804): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  804): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  804): unregisterListener ::   
D/LightsService(  804): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  292): adev_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  292): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  804): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  804): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  804): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  804): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  804): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1466): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 2225): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2225): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/DisplayPowerState(  804): !@ ColorFade entry
,D/DisplayPowerController(  804): ColorFade: onAnimationEnd
D/accuweather( 2225): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,E/LightSensor(  804): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  804): mCallbacks.updateBrightness()
,D/AutomaticBrightnessController(  804): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  804): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  804): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  804): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  804): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  804): unregisterListener ::   
,E/Sensors (  804): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  804): unregisterListener ::   
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerController(  804): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  804): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  804): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  804): Display changed displayId=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/SSRM:m  (  804): SIOP:: AP = 340, PST = 397, CUR = 300
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/X       (  804): broadcastSiopLevelIntent:: currentSiopLevel = -1
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,W/ActivityManager(  804): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/ContentApp( 1220):  LEVEL : -1
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SystemBroadcastReceiver( 7205): [#DCM#] [DCM_Performance] onReceive completed in time  377 microsec. 
,I/SystemBroadcastReceiver( 7205): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7205): [#DCM#] onReceive action = EVENT_SIOP
,E/Zygote  ( 8238): MountEmulatedStorage()
,E/Zygote  ( 8238): v2
I/libpersona( 8238): KNOX_SDCARD checking this for 10054
I/libpersona( 8238): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8238 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,W/ActivityManager(  804): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/SELinux ( 8238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/SystemBroadcastReceiver( 7205): [#DCM#] [DCM_Performance] onReceive completed in time  76 microsec. 
,I/SystemBroadcastReceiver( 7205): [#DCM#] Calling notifyListeners. 
E/SELinux ( 8238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DCMPolicyManager( 7205): [#DCM#] onReceive action = EVENT_SCREEN_OFF
,I/DCMController( 7205): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  804): [PWL] sb release: PowerManagerService.Broadcasts
,D/TimaKeyStoreProvider( 8238): TimaSignature is unavailable
,D/ActivityThread( 8238): Added TimaKeyStore provider
,D/ResourcesManager( 8238): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8238): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8238): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,E/SMD     (  287): DCD ON
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  275): 
,I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,E/TranscodeReceiver( 8238): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8238): core_num = 4
,W/linker  ( 8238): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8238): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  804): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService(  804): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  804): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  804): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  804): Got set_interactive hint
,I/PowerManagerService(  804): [PWL] Off : 0s ago
I/PowerManagerService(  804): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  804): [PWL]     mDisplayReady : false
D/DisplayPowerController(  804): getFinalBrightness : 0 -> 0
D/PowerManagerService(  804): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  804): [PWL] sb release: PowerManagerService.Display
,D/videowall-Global( 8238): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8238): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8238):  SIOP_LEVEL: -1
,I/ActivityManager(  804): Killing 7103:com.samsung.helphub/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  804): failed to open /acct/uid_1000/pid_7103/cgroup.procs: No such file or directory
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...,
,V/AlarmManager(  804): waitForAlarm result :4
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/BatteryService(  804): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6689): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6689): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6689): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  804): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  804): [PWL] Off : 5s ago
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 330, PST = 384, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  804): [PWL] Off : 15s ago
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  804): waitForAlarm result :4
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  804): stay LED for fully charged
D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
I/MotionRecognitionService(  804): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6662): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at kff.l(PG:132)
E/HttpOperation( 6662): 	at dsf.a(PG:807)
E/HttpOperation( 6662): 	at fhk.a(PG:1126)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 8 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 10 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6662): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at kff.l(PG:132)
E/HttpOperation( 6662): 	at ieo.a(PG:43)
E/HttpOperation( 6662): 	at iep.a(PG:93)
E/HttpOperation( 6662): 	at fhn.a(PG:59)
E/HttpOperation( 6662): 	at lex.a(PG:85)
E/HttpOperation( 6662): 	at lex.b(PG:132)
E/HttpOperation( 6662): 	at fhk.a(PG:1146)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 12 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 14 more
,E/ExperimentLoader( 6662): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6662): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6662): 	at kfv.a(PG:65)
E/ExperimentLoader( 6662): 	at kff.u(PG:385)
E/ExperimentLoader( 6662): 	at kfb.a(PG:29)
E/ExperimentLoader( 6662): 	at kff.l(PG:132)
E/ExperimentLoader( 6662): 	at ieo.a(PG:43)
E/ExperimentLoader( 6662): 	at iep.a(PG:93)
E/ExperimentLoader( 6662): 	at fhn.a(PG:59)
E/ExperimentLoader( 6662): 	at lex.a(PG:85)
E/ExperimentLoader( 6662): 	at lex.b(PG:132)
E/ExperimentLoader( 6662): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6662): 	at fhk.a(PG:908)
E/ExperimentLoader( 6662): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6662): 	at ihi.a(PG:22)
E/ExperimentLoader( 6662): 	at kft.a(PG:91)
E/ExperimentLoader( 6662): 	at kfv.a(PG:62)
E/ExperimentLoader( 6662): 	... 12 more
E/ExperimentLoader( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6662): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6662): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6662): 	at ihi.a(PG:19)
E/ExperimentLoader( 6662): 	... 14 more
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6662): [getaccountstatus] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at ixd.a(PG:248)
E/HttpOperation( 6662): 	at ixd.b(PG:206)
E/HttpOperation( 6662): 	at ixd.a(PG:175)
E/HttpOperation( 6662): 	at fig.a(PG:78)
E/HttpOperation( 6662): 	at lex.a(PG:85)
E/HttpOperation( 6662): 	at lex.b(PG:132)
E/HttpOperation( 6662): 	at fhk.a(PG:1146)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 12 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 14 more
,E/EsSyncAdapterService( 6662): Sync failure
E/EsSyncAdapterService( 6662): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6662): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6662): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6662): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6662): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6662): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6662): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6662): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6662): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6662): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6662): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6662): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6662): 	... 10 more
E/EsSyncAdapterService( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6662): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6662): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6662): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6662): 	... 12 more
E/EsSyncAdapterService( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6662): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6662): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6662): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6662): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  804): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 125577, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  804): Explicit concurrent mark sweep GC freed 82085(4MB) AllocSpace objects, 26(3MB) LOS objects, 29% free, 38MB/54MB, paused 1.272ms total 109.542ms
D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  804): mCursor = null
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 330, PST = 376, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  804): waitForAlarm result :4
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6689): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6689): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6689): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/BatteryService(  804): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,E/Watchdog(  804): !@Sync 5
,D/SSRM:m  (  804): SIOP:: AP = 320, PST = 367, CUR = 300
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  804): [PWL] Off : 30s ago
,E/SMD     (  287): DCD ON
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 320, PST = 358, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  804): waitForAlarm result :8
,V/AlarmManager(  804): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1693): Vacuum at: now=1453416060865 tag=VacuumService
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1693): Using platform SSLCertificateSocketFactory
,W/Uploader( 1693): No account for auth token provided
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1693): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1693): (HTTPLog)-Static: isShipBuild true
I/System.out( 1693): (HTTPLog)-Thread-210-625351827: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1693): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,I/qtaguid ( 1693): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1693): Explicit concurrent mark sweep GC freed 49801(2MB) AllocSpace objects, 24(1834KB) LOS objects, 39% free, 18MB/30MB, paused 1.132ms total 226.936ms
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6689): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6689): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6689): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/Uploader( 1693): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1693): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1693): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1693): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1693): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693): No account for auth token provided
,I/qtaguid ( 1693): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,W/Uploader( 1693):  no longer exists, so no auth token.
,I/qtaguid ( 1693): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1693, getuid(): 10012
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/AlarmManager(  804): waitForAlarm result :4
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7374): Starting books sync, d
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7374): null auth token
,I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Untagging socket 34
,W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
,W/ApiaryClient( 7374): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5310539522925382309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  287): DCD ON
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7374): null auth token
,I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Untagging socket 34
,W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
,W/ApiaryClient( 7374): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5310539522925382309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7374): null auth token
,I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Untagging socket 34
,W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
,W/ApiaryClient( 7374): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5310539522925382309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  804): SIOP:: AP = 320, PST = 352, CUR = 300
,I/PowerManagerService(  804): [PWL] Off : 50s ago
,I/PowerManagerService(  804): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  804): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  804): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=804, ws=WorkSource{10082}) (elapsedTime=3621)
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/BooksSync( 7374): Soft error
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5310539522925382309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7374): Headers suppressed
E/BooksSync( 7374): 
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7374): Sync error
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5310539522925382309&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7374): Headers suppressed
E/BooksSync( 7374): 
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7374): Finished books sync
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  804): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159822, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  804): mCursor = null
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1693): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
E/HttpOperation( 6662): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at kff.l(PG:132)
E/HttpOperation( 6662): 	at dsf.a(PG:807)
E/HttpOperation( 6662): 	at fhk.a(PG:1126)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 8 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 10 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6662): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at kff.l(PG:132)
E/HttpOperation( 6662): 	at ieo.a(PG:43)
E/HttpOperation( 6662): 	at iep.a(PG:93)
E/HttpOperation( 6662): 	at fhn.a(PG:59)
E/HttpOperation( 6662): 	at lex.a(PG:85)
E/HttpOperation( 6662): 	at lex.b(PG:132)
E/HttpOperation( 6662): 	at fhk.a(PG:1146)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 12 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 14 more
,E/ExperimentLoader( 6662): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6662): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6662): 	at kfv.a(PG:65)
E/ExperimentLoader( 6662): 	at kff.u(PG:385)
E/ExperimentLoader( 6662): 	at kfb.a(PG:29)
E/ExperimentLoader( 6662): 	at kff.l(PG:132)
E/ExperimentLoader( 6662): 	at ieo.a(PG:43)
E/ExperimentLoader( 6662): 	at iep.a(PG:93)
E/ExperimentLoader( 6662): 	at fhn.a(PG:59)
E/ExperimentLoader( 6662): 	at lex.a(PG:85)
E/ExperimentLoader( 6662): 	at lex.b(PG:132)
E/ExperimentLoader( 6662): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6662): 	at fhk.a(PG:908)
E/ExperimentLoader( 6662): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6662): 	at ihi.a(PG:22)
E/ExperimentLoader( 6662): 	at kft.a(PG:91)
E/ExperimentLoader( 6662): 	at kfv.a(PG:62)
E/ExperimentLoader( 6662): 	... 12 more
E/ExperimentLoader( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6662): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6662): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6662): 	at ihi.a(PG:19)
E/ExperimentLoader( 6662): 	... 14 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6662): [getaccountstatus] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at ixd.a(PG:248)
E/HttpOperation( 6662): 	at ixd.b(PG:206)
E/HttpOperation( 6662): 	at ixd.a(PG:175)
E/HttpOperation( 6662): 	at fig.a(PG:78)
E/HttpOperation( 6662): 	at lex.a(PG:85)
E/HttpOperation( 6662): 	at lex.b(PG:132)
E/HttpOperation( 6662): 	at fhk.a(PG:1146)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 12 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 14 more
,E/SMD     (  287): DCD ON
,E/EsSyncAdapterService( 6662): Sync failure
E/EsSyncAdapterService( 6662): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6662): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6662): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6662): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6662): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6662): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6662): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6662): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6662): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6662): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6662): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6662): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6662): 	... 10 more
E/EsSyncAdapterService( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6662): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6662): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6662): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6662): 	... 12 more
E/EsSyncAdapterService( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6662): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6662): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6662): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6662): 	... 14 more
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  804): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 185630, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  804): mCursor = null
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,I/art     (  804): Explicit concurrent mark sweep GC freed 40983(2MB) AllocSpace objects, 20(775KB) LOS objects, 29% free, 38MB/54MB, paused 1.785ms total 185.124ms
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  804): !@Sync 6
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 310, PST = 343, CUR = 300
,E/SMD     (  287): DCD ON,
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/BatteryService(  804): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 310, PST = 333, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  804): [PWL] Off : 75s ago
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager(  804): waitForAlarm result :4
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  804): stay LED for fully charged
D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
I/MotionRecognitionService(  804): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 310, PST = 325, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,E/Watchdog(  804): !@Sync 7
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 319, CUR = 300
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD ON
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 315, CUR = 300
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,V/AlarmManager(  804): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  804): [PWL] Off : 105s ago
,V/AlarmManager(  804): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  804): stay LED for fully charged
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7374): Starting books sync, d
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
D/SecContentProvider2(  804): mCursor = null
,D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpHelper( 7374): null auth token
,I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Untagging socket 34
,W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
,W/ApiaryClient( 7374): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5670744609372214241&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7374): null auth token
,I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Untagging socket 34
,W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
,W/ApiaryClient( 7374): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5670744609372214241&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1693): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1693): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1693): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1693): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1693): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7374): Authentication error
E/BooksAccountManager( 7374): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7374): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7374): null auth token
,I/qtaguid ( 7374): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7374, getuid(): 10082
,I/qtaguid ( 7374): Untagging socket 34
,W/ApiaryClient( 7374): Error response from books API: {
W/ApiaryClient( 7374):  "error": {
W/ApiaryClient( 7374):   "errors": [
W/ApiaryClient( 7374):    {
W/ApiaryClient( 7374):     "domain": "global",
W/ApiaryClient( 7374):     "reason": "required",
W/ApiaryClient( 7374):     "message": "Login Required",
W/ApiaryClient( 7374):     "locationType": "header",
W/ApiaryClient( 7374):     "location": "Authorization"
W/ApiaryClient( 7374):    }
W/ApiaryClient( 7374):   ],
W/ApiaryClient( 7374):   "code": 401,
W/ApiaryClient( 7374):   "message": "Login Required"
W/ApiaryClient( 7374):  }
W/ApiaryClient( 7374): }
,W/ApiaryClient( 7374): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5670744609372214241&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7374): Headers suppressed
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 312, CUR = 300
,E/BooksSync( 7374): Soft error
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5670744609372214241&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7374): Headers suppressed
E/BooksSync( 7374): 
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7374): Sync error
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7374): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5670744609372214241&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7374): Headers suppressed
E/BooksSync( 7374): 
E/BooksSync( 7374): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7374): Finished books sync
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  804): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 219971, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  804): mCursor = null
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...,
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,D/BatteryService(  804): stay LED for fully charged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/Watchdog(  804): !@Sync 8
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 309, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 307, CUR = 300
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  804): waitForAlarm result :4
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6662): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at kff.l(PG:132)
E/HttpOperation( 6662): 	at dsf.a(PG:807)
E/HttpOperation( 6662): 	at fhk.a(PG:1126)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 8 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 10 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
,D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6662): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at kff.l(PG:132)
E/HttpOperation( 6662): 	at ieo.a(PG:43)
E/HttpOperation( 6662): 	at iep.a(PG:93)
E/HttpOperation( 6662): 	at fhn.a(PG:59)
E/HttpOperation( 6662): 	at lex.a(PG:85)
E/HttpOperation( 6662): 	at lex.b(PG:132)
E/HttpOperation( 6662): 	at fhk.a(PG:1146)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 12 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 14 more
,E/ExperimentLoader( 6662): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6662): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6662): 	at kfv.a(PG:65)
E/ExperimentLoader( 6662): 	at kff.u(PG:385)
E/ExperimentLoader( 6662): 	at kfb.a(PG:29)
E/ExperimentLoader( 6662): 	at kff.l(PG:132)
E/ExperimentLoader( 6662): 	at ieo.a(PG:43)
E/ExperimentLoader( 6662): 	at iep.a(PG:93)
E/ExperimentLoader( 6662): 	at fhn.a(PG:59)
E/ExperimentLoader( 6662): 	at lex.a(PG:85)
E/ExperimentLoader( 6662): 	at lex.b(PG:132)
E/ExperimentLoader( 6662): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6662): 	at fhk.a(PG:908)
E/ExperimentLoader( 6662): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6662): 	at ihi.a(PG:22)
E/ExperimentLoader( 6662): 	at kft.a(PG:91)
E/ExperimentLoader( 6662): 	at kfv.a(PG:62)
E/ExperimentLoader( 6662): 	... 12 more
E/ExperimentLoader( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6662): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6662): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6662): 	at ihi.a(PG:19)
E/ExperimentLoader( 6662): 	... 14 more
,I/GLSUser ( 1693): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1693): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1693): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1693): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1693): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  804): uri = 14 selection = getSealedState
,D/SecContentProvider2(  804): mCursor = null
D/SecContentProvider2(  804): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  804): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  804): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6662): [getaccountstatus] Unexpected exception
E/HttpOperation( 6662): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6662): 	at kfv.a(PG:65)
E/HttpOperation( 6662): 	at kff.u(PG:385)
E/HttpOperation( 6662): 	at kfb.a(PG:29)
E/HttpOperation( 6662): 	at ixd.a(PG:248)
E/HttpOperation( 6662): 	at ixd.b(PG:206)
E/HttpOperation( 6662): 	at ixd.a(PG:175)
E/HttpOperation( 6662): 	at fig.a(PG:78)
E/HttpOperation( 6662): 	at lex.a(PG:85)
E/HttpOperation( 6662): 	at lex.b(PG:132)
E/HttpOperation( 6662): 	at fhk.a(PG:1146)
E/HttpOperation( 6662): 	at fhk.a(PG:908)
E/HttpOperation( 6662): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6662): 	at ihi.a(PG:22)
E/HttpOperation( 6662): 	at kft.a(PG:91)
E/HttpOperation( 6662): 	at kfv.a(PG:62)
E/HttpOperation( 6662): 	... 12 more
E/HttpOperation( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6662): 	at gde.c(Unknown Source)
E/HttpOperation( 6662): 	at gde.b(Unknown Source)
E/HttpOperation( 6662): 	at ihi.a(PG:19)
E/HttpOperation( 6662): 	... 14 more
,E/EsSyncAdapterService( 6662): Sync failure
E/EsSyncAdapterService( 6662): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6662): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6662): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6662): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6662): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6662): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6662): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6662): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6662): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6662): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6662): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6662): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6662): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6662): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6662): 	... 10 more
E/EsSyncAdapterService( 6662): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6662): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6662): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6662): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6662): 	... 12 more
E/EsSyncAdapterService( 6662): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6662): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6662): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6662): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6662): 	... 14 more
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  804): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 252248, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  804): mCursor = null
,E/SMD     (  287): DCD ON
,E/SQLiteLog( 1693): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  804): [PWL] Off : 140s ago
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 305, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/BatteryService(  804): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,E/Watchdog(  804): !@Sync 9
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,I/ServiceManager(  320): Waiting for service AtCmdFwd...
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 302, CUR = 300
,W/Atfwd_Sendcmd(  320): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,V/AlarmManager(  804): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,V/AlarmManager(  804): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  804): stay LED for fully charged
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
I/MotionRecognitionService(  804): setPowerConnected  = true
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/TimaService(  804): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  804): TimaServiceHandler.handleMessage what =1
,D/TimaService(  804): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  804): initializing...
,I/TLC_TIMA_PKM_initialize(  804): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  804): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  804): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  804): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  804): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  804): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  804): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  804): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  804): App is not loaded in QSEE
,D/QSEECOMAPI: (  804): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  804): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  804): Trustlet response is completed
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  804): !@Sync 10
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/BatteryService(  804): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  804): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  804): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  804): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  804): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  804): [PWL] Off : 180s ago
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  320): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  320): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  804): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  804): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  804): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  804):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  804): Plugged
,I/MotionRecognitionService(  804): setPowerConnected  = true
,D/BatteryService(  804): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3237): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3237): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  804): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7448): --= Surplus to requirements =--
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): ****TEST TOOK:  ms ****
I/jxcore-log( 7448): 
,I/jxcore-log( 7448): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7448): 
,D/AndroidRuntime( 8471): 
D/AndroidRuntime( 8471): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8471): CheckJNI is OFF
,D/AndroidRuntime( 8471): setted country_code = Germany
D/AndroidRuntime( 8471): setted countryiso_code = DE
,D/AndroidRuntime( 8471): setted sales_code = DBT
,D/AndroidRuntime( 8471): readGMSProperty: start
,D/AndroidRuntime( 8471): readGMSProperty: already setted!!
D/AndroidRuntime( 8471): readGMSProperty: end
D/AndroidRuntime( 8471): addProductProperty: start
,E/AffinityControl( 8471): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8471): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  804): START PACKAGE DELETE: observer{803590599}
D/PackageManager(  804): pkg{<packageName>}
D/PackageManager(  804): user{0}
D/PackageManager(  804): caller{2000}
D/PackageManager(  804): flags{3}
,D/PersonaManagerService(  804): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  804): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  804): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  804): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  804): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  804): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  804): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  804): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  804): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  804): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  804): !@killApplicatoin: 10200, uninstall pkg
,I/ActivityManager(  804): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
I/ActivityManager(  804): Killing 7448:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
,I/ActivityManager(  804):   Force finishing activity ActivityRecord{105f2396 u0 com.test.thalitest/.MainActivity t18}
,D/FocusedStackFrame(  804): Set to : 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/WifiService(  804): Client connection lost with reason: 4
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  804): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
,I/art     ( 4443): Explicit concurrent mark sweep GC freed 5010(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 330us total 30.459ms
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1862): mOCRHelper is null
,W/GeofencerStateMachine( 2127): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.4.503: ( 7660): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7660): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1453416211173
,I/KLMS-2.4.503: ( 7660): MainReciver(): PACKAGE_REMOVED
,I/InputReader(  804): Reconfiguring input devices.  changes=0x00000010
I/KLMS-2.4.503: ( 7660): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 2846): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/art     ( 1573): Explicit concurrent mark sweep GC freed 54529(3MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 475us total 80.675ms
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  804): Explicit concurrent mark sweep GC freed 48273(3MB) AllocSpace objects, 55(1270KB) LOS objects, 29% free, 38MB/54MB, paused 3.563ms total 151.729ms
I/art     (  804): WaitForGcToComplete blocked for 55.203ms for cause Explicit
D/ResourcesManager(  804): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 2846): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/SecContentProvider2(  804): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  804): mCursor = null
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  ( 8502): MountEmulatedStorage()
I/libpersona( 8502): KNOX_SDCARD checking this for 10104
E/Zygote  ( 8502): v2
I/libpersona( 8502): KNOX_SDCARD not a persona
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager(  804): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8502 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux ( 8502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/RegisteredServicesCache( 1466): empty dynamic service
,E/SELinux ( 8502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/TimaKeyStoreProvider( 8502): TimaSignature is unavailable
D/ActivityThread( 8502): Added TimaKeyStore provider
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/EnterpriseDeviceManagerService(  804): Package has changed for user 0
D/EnterpriseDeviceManagerService(  804): Admin package name: com.google.android.gms
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 8502): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1486): destroyHardwareResources():1038728087
,V/WindowOrientationListener(  804): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  804): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  804): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  804): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  804): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/Launcher( 1486): onRestart, Launcher: 907921248
D/Launcher( 1486): onStart, Launcher: 907921248
D/Launcher.HomeView( 1486): onStart
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2225): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2225): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/elm:14451( 8502): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/elm:14451( 8502): ELMEngine.ELMEngine( context ).
,I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  804): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBarManagerService(  804): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/elm:14451( 8502): MDMBridge.setEnterpriseBridge()
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/InputMethodManagerService(  804): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/elm:14451( 8502): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/ContextImpl(  804): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:14451( 8502): ElmAgentService : onCreate()
,W/InputMethodManagerService(  804): Got RemoteException sending setActive(false) notification to pid 7448 uid 10200
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8023): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 8023): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8023): onReceive() : package name is not s health. Return !!!
,D/elm:14451( 8502): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/elm:14451( 8502): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8502): MDMBridge.getInstance()
,D/elm:14451( 8502): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_PushUtil( 6818): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6818): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6818): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6818): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/RCPManagerService(  804): PackageReceiver onReceive()
I/HarmonyEASService(  804): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  804): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:14451( 8502): MDMBridge.getAllLicenseInfoFromSDK()
,D/BackupManagerService(  804): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  804): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  804): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  804): uID is 10200
V/EnterpriseBillingPolicy(  804): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  804): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  804): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  804): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  804): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  804): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  804): getBillingProfileForVpnEngine - end - null
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/elm:14451( 8502): ElmAgentService : onDestroy().
,D/TaskPersister(  804): removeObsoleteFile: deleting file=18_task.xml
,D/TaskPersister(  804): removeObsoleteFile: deleting file=18_task_thumbnail.png
,I/art     (  804): Explicit concurrent mark sweep GC freed 12380(583KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 38MB/54MB, paused 8.594ms total 245.337ms
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/Zygote  ( 8525): MountEmulatedStorage()
E/Zygote  ( 8525): v2
I/libpersona( 8525): KNOX_SDCARD checking this for 10038
I/libpersona( 8525): KNOX_SDCARD not a persona
,I/Timeline(  804): Timeline: Activity_windows_visible id: ActivityRecord{12bf22e9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:331062
I/ActivityManager(  804): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8525 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/PackageManager(  804): delete codoeFile: 
,D/PackageManager(  804): result of delete: 1{803590599}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/art     (  313): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 12.721ms
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 8.196ms
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 299us total 7.815ms
,I/SELinux ( 8525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SELinux ( 8525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ActivityManager(  804): Killing 7144:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
E/SELinux ( 8525): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/AndroidRuntime( 8471): Shutting down VM
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  804): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  804): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  804): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/TimaKeyStoreProvider( 8525): TimaSignature is unavailable
D/ActivityThread( 8525): Added TimaKeyStore provider
,D/ResourcesManager(  804): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager( 8525): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  804): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  804): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  804): clearDefaults: com.test.thalitest
,W/libprocessgroup(  804): failed to open /acct/uid_10166/pid_7144/cgroup.procs: No such file or directory
,I/CrashAnrDetector(  804): onPackageRemoved : com.test.thalitest
D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/SPPClientService( 8525): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8525): [PushClientApplication] Push log off : This is Ship build version
,W/ResourcesManager( 7970): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/SPPClientService( 8525): PushLog.txt file is not deleted.
D/SPPClientService( 8525): PushLog.txt file is not deleted.
D/SPPClientService( 8525): ============PushLog. stop!
,W/ResourcesManager( 7970): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 7970): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 8541): MountEmulatedStorage()
,E/Zygote  ( 8541): v2
D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/libpersona( 8541): KNOX_SDCARD checking this for 10042
I/libpersona( 8541): KNOX_SDCARD not a persona
,W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager(  804): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8541 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,W/ResourcesManager( 7970): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager(  804): Killing 6736:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 8541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8541): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/TimaKeyStoreProvider( 8541): TimaSignature is unavailable
,W/ResourcesManager( 7970): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/ActivityThread( 8541): Added TimaKeyStore provider
W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8541): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/libprocessgroup(  804): failed to open /acct/uid_10012/pid_6736/cgroup.procs: No such file or directory
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8541): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8541): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7970): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7970): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7970): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/System.err( 8541): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
,W/System.err( 8541): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 8541): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 8541): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 8541): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 8541): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 8541): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 8541): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 8541): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 8541): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 8541): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 8541): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 8541): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 8541): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 8541): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8541): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8541): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8541): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8541): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8541): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SL_DEBUG( 8541): isLoggable:: isProductShip = 1
I/SL_DEBUG( 8541): isLoggable:: SL_DEBUG_EXIST = false
,D/ConnectivityService(  804): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8541): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8541): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,V/Transcoder( 8541): Transcoder(0xaedf18d0)::constructor
V/Transcoder( 8541): addObitRecipient
V/TMI-JNI ( 8541): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,I/SA      ( 6853): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6853): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10200 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1797): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77df5050 in tid 1797 (d.process.acore)
,E/audit_log( 2060): File locking failed. error= Bad file number
,E/audit_log( 2060): File locking failed. error= Bad file number
,E/audit_log( 2060): File locking failed. error= Bad file number
,E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  804): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  804): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 8571): MountEmulatedStorage()
,E/Zygote  ( 8571): v2
I/libpersona( 8571): KNOX_SDCARD checking this for 10050
I/libpersona( 8571): KNOX_SDCARD not a persona
,I/ActivityManager(  804): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8571 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SharedPreferencesImpl( 6048): Couldn't create directory for SharedPreferences file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml
,F/libc    ( 8541): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa16f5a00 in tid 8541 (sdk.samsunglink)
,F/libc    ( 8541): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2060): File locking failed. error= Bad file number
,I/EventHub(  804): Removing device '/dev/input/event4' due to inotify event
,I/SELinux ( 8571): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8571): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Zygote  (  313): Process 1797 exited due to signal (7)
,I/ActivityManager(  804): Process android.process.acore (pid 1797)(adj 0) has died(185,521)
,F/libc    (  804): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0d99810 in tid 1671 (Binder_C)
E/audit_log( 2060): File locking failed. error= Bad file number
F/libc    (  804): Unable to open connection to debuggerd: Connection refused
,E/SMD     (  287): DCD ON
,I/Zygote  (  313): Process 8541 exited due to signal (7)
,I/ServiceManager(  247): service 'mum_container_policy' died
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
I/ServiceManager(  247): service 'wifi' died
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/ServiceManager(  247): service 'location' died
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
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
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
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'backup' died
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'wifip2p' died
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
E/audit_log( 2060): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'input_method' died,
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
F/libc    ( 8571): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759acd71 in tid 8571 (com.android.mms)
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
I/ServiceManager(  247): service 'usagestats' died
F/libc    ( 8571): Unable to open connection to debuggerd: Connection refused
W/Sensors ( 1486): sensorservice died [0xaed63400]
E/WifiManager( 1169): Channel connection lost
W/Sensors ( 1169): sensorservice died [0xaedd20c0]
E/WifiManager( 1573): Channel connection lost
E/WifiManager( 2127): Channel connection lost
F/libc    ( 4443): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758bd083 in tid 4488 (AppProvider)
I/SurfaceFlinger(  249): id=18 Removed ColorFade (8/8)
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
F/libc    ( 4443): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2060): File locking failed. error= Bad file number
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (4/7)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/6)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/5)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (0/4)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (2/3)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/3)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/3)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/3)
W/AudioFlinger(  292): power manager service died !!!
W/AudioFlinger(  292): power manager service died !!!
E/WifiManager( 1472): Channel connection lost
W/Sensors ( 1459): sensorservice died [0xaedbfbc0]
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/3)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/3)
W/Sensors ( 1472): sensorservice died [0xaed63380]
,W/Sensors ( 2127): sensorservice died [0xaedc2ec0]
F/libc    ( 2107): Fatal signal 7 (SIGBUS), code 2, fault addr 0x76489f18 in tid 2150 (Binder_1)
F/libc    ( 2107): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2060): File locking failed. error= Bad file number
E/WifiManager( 5625): Channel connection lost
E/WifiManager( 1292): Channel connection lost
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (0/2)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/2)
I/SurfaceFlinger(  249): id=19 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (0/1)
I/SurfaceFlinger(  249): id=19 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/1)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (0/0)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/0)
I/SurfaceFlinger(  249): id=18 Removed ColorFade (-2/0)
W/Sensors ( 1292): sensorservice died [0x9d6212c0]
W/Sensors ( 2144): sensorservice died [0xaedbfc00]
W/Sensors ( 6048): sensorservice died [0xaed67540]
I/Zygote  (  313): Process 8571 exited due to signal (7)
,I/Zygote  (  313): Process 2107 exited due to signal (7)
I/Zygote  (  313): Process 4443 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
E/qdhwcomposer(  249): hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
E/SurfaceFlinger(  249): eventControl(0, 1) failed Operation not permitted
,E/installd(  296): eof
E/installd(  296): failed to read size
I/installd(  296): closing connection
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
