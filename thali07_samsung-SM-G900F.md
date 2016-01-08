#### Test 55431344e5dd625_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7388): null auth token
I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
I/qtaguid ( 7388): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
I/qtaguid ( 7388): Untagging socket 34
W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
W/ApiaryClient( 7388): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6725407469043300314&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
--------- beginning of system
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7430): 
D/AndroidRuntime( 7430): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7430): CheckJNI is OFF
D/AndroidRuntime( 7430): setted country_code = Germany
D/AndroidRuntime( 7430): setted countryiso_code = DE
D/AndroidRuntime( 7430): setted sales_code = DBT
D/AndroidRuntime( 7430): readGMSProperty: start
D/AndroidRuntime( 7430): readGMSProperty: already setted!!
D/AndroidRuntime( 7430): readGMSProperty: end
D/AndroidRuntime( 7430): addProductProperty: start
E/AffinityControl( 7430): AffinityControl: registerfunction enter
D/AndroidRuntime( 7430): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  816): inState():  stateMachine is null !!
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  816): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  816): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  816): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  816): mDVFSHelper.acquire()
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
D/AndroidRuntime( 7430): Shutting down VM
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
I/SQLiteSecureOpenHelper( 3578): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3578): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/SMD     (  282): DCD ON
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 47
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  816): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 816) 
D/LightsService(  816): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  816): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  816): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1169): Icon Only
D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  816): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3819): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
D/KnoxNotification( 1169): ----- inflateViews : modified publicViewLocal -----
I/DBG_DM  ( 3819): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1169): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@1ded0143
D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1169): Icon Only
E/Zygote  ( 7465): MountEmulatedStorage()
E/Zygote  ( 7465): v2
I/libpersona( 7465): KNOX_SDCARD checking this for 10367
I/libpersona( 7465): KNOX_SDCARD not a persona
I/ActivityManager(  816): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7465 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7465): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
D/TimaKeyStoreProvider( 7465): TimaSignature is unavailable
D/ActivityThread( 7465): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
V/ActivityManager(  816): Display changed displayId=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  816): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 7465): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/WebViewFactory( 7465): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7465): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/LibraryLoader( 7465): Loading: webviewchromium
I/LibraryLoader( 7465): Time to load native libraries: 3 ms (timestamps 4939-4942)
I/LibraryLoader( 7465): Expected native library version number "",actual native library version number ""
I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
V/WebViewChromiumFactoryProvider( 7465): Binding Chromium to main looper Looper (main, tid 1) {25228b4}
I/LibraryLoader( 7465): Expected native library version number "",actual native library version number ""
I/chromium( 7465): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7465): Initializing chromium process, renderers=0
W/art     ( 7465): Attempt to remove local handle scope entry from IRT, ignoring
V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
W/chromium( 7465): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7465): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7465): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7388): null auth token
I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
I/Adreno-EGL( 7465): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7465): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7465): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7465): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7465): Remote Branch: 
I/Adreno-EGL( 7465): Local Patches: 
I/Adreno-EGL( 7465): Reconstruct Branch: 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/qtaguid ( 7388): Untagging socket 34
W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ApiaryClient( 7388): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6725407469043300314&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
W/chromium( 7465): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/chromium( 7465): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7465): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7465): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SystemWebViewEngine( 7465): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 7465): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7465): Attempt to remove local handle scope entry from IRT, ignoring
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
D/Activity( 7465): performCreate Call secproduct feature valuefalse
D/Activity( 7465): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/OpenGLRenderer( 7465): Render dirty regions requested: true
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ActivityManager(  816): post active user change for 0
D/KnoxTimeoutHandler(  816): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  816): handleActiveUserChange for user 0
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
D/LockPatternUtilsCache( 1169): value : false
I/OpenGLRenderer( 7465): Initialized EGL, version 1.4
I/OpenGLRenderer( 7465): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7465): Enabling debug mode 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/InputMethodManagerService(  816): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Adreno-ES20( 7465): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7465): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/ActivityManager(  816): Displayed com.test.thalitest/.MainActivity: +705ms
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
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/art     (  816): Explicit concurrent mark sweep GC freed 62953(3MB) AllocSpace objects, 19(1779KB) LOS objects, 29% free, 37MB/53MB, paused 1.518ms total 132.869ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
D/JsMessageQueue( 7465): Set native->JS mode to OnlineEventsBridgeMode
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/CustomFrequencyManagerService(  816): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  816): mDVFSHelper.release()
I/Timeline(  816): Timeline: Activity_windows_visible id: ActivityRecord{3e82826c u0 com.test.thalitest/.MainActivity t12} time:95536
D/CustomFrequencyManagerService(  816): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline( 7465): Timeline: Activity_idle id: android.os.BinderProxy@36f54a77 time:95542
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/chromium( 7465): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7465): 
,D/jxcore_app_log( 7465): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358533504
,D/JX-Cordova( 7465): jxcore cordova android initializing
,D/CustomFrequencyManagerService(  816): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  tag : ACTIVITY_RESUME_BOOSTER@10
,E/BooksSync( 7388): Soft error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6725407469043300314&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7388): Sync error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6725407469043300314&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7388): Finished books sync
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  816): Killing 6582:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62520, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  816): mCursor = null
,W/libprocessgroup(  816): failed to open /acct/uid_10075/pid_6582/cgroup.procs: No such file or directory
,D/PowerManagerService(  816): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
,W/ProcessCpuTracker(  816): Skipping unknown process pid 7461
,W/ProcessCpuTracker(  816): Skipping unknown process pid 7464
,I/GAV2    ( 7388): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  816): waitForAlarm result :4
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/SSRM:m  (  816): SIOP:: AP = 360, PST = 418, CUR = 300
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6690): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6690): [1] 5.onFinished: Scheduling replication attempt 2.
,W/jxcore-log( 7465): Initializing JXcore engine
W/jxcore-log( 7465): JXcore engine is ready
,W/jxcore-log( 7465): Starting JXcore engine
,E/auditd  ( 2022): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  816): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  816): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7538): MountEmulatedStorage()
E/Zygote  ( 7538): v2
I/libpersona( 7538): KNOX_SDCARD checking this for 1000
I/libpersona( 7538): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7538 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7538): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 7465): Platform android
W/jxcore-log( 7465): 
W/jxcore-log( 7465): Process ARCH arm
W/jxcore-log( 7465): 
,D/TimaKeyStoreProvider( 7538): TimaSignature is unavailable
,D/ActivityThread( 7538): Added TimaKeyStore provider
,D/ResourcesManager( 7538): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7538):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7538):  SeDenialReceiver : File path = null
,I/ActivityManager(  816): Killing 6611:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  816): failed to open /acct/uid_1000/pid_6611/cgroup.procs: No such file or directory
,E/SMD     (  282): DCD ON
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,I/jxcore-log( 7465): JXcore Cordova bridge is ready!
I/jxcore-log( 7465): 
W/jxcore-log( 7465): JXcore engine is started
,D/TaskPersister(  816): removeObsoleteFile: deleting file=11_task_thumbnail.png
,I/jxcore-log( 7465): Toggling radios to true
I/jxcore-log( 7465): 
,D/BluetoothAdapter( 7465): enable()
,D/BluetoothAdapter( 7465): enable(): BT is already enabled..!
,D/WifiService(  816): New client listening to asynchronous messages
,I/WifiManager( 7465): packageName : com.test.thalitest
,D/SecContentProvider(  816): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  816): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  816): mCursor = null
,D/WifiService(  816): setWifiEnabled: true pid=7465, uid=10367
E/WifiService(  816): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  816): Permission Denial: getCurrentUser() from pid=7465, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  816): Failed getting userId using ActivityManagerNative
W/WifiService(  816): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7465, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  816): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  816): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  816): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  816): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  816): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  816): name = wifi_on
,I/WifiService(  816): disconnect: pid=7465, uid=10367
,I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7465): Radios toggled
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Received device characteristics:
I/jxcore-log( 7465): Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7465): Bluetooth name: Thali Test (Galaxy S5)
I/jxcore-log( 7465): Device name: samsung-SM-G900F
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Perf Test app loaded loaded
I/jxcore-log( 7465): 
,I/chromium( 7465): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 7465): Skipped 73 frames!  The application may be doing too much work on its main thread.
,I/wpa_supplicant( 1269): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1269): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1269): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1269): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  816): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1269): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1269): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1269): Disconnected - do not scan
I/wpa_supplicant( 1269): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine(  816): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  816): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  816): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  816): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  816): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  816): InactiveState{ what=143375 }
,D/WifiP2pService(  816): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/jxcore-log( 7465): check test folder
I/jxcore-log( 7465): 
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,I/jxcore-log( 7465): found test : ./testFindPeers.js
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): found test : ./testSendData.js
I/jxcore-log( 7465): 
,V/NativeCrypto( 1692): Read error: ssl=0xad444600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1692): SSL shutdown failed: ssl=0xad444600: I/O error during system call, Broken pipe
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): Validated
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  816): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  816):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  816):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  816): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  816): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  816): calling update connectivity
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/WifiStateMachine(  816): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
E/ConnectivityService(  816): updateNetworkInfo()
,D/ConnectivityService(  816): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  816): updateNetworkInfo()
D/ConnectivityService(  816): ignoring duplicate network state non-change
D/ConnectivityService(  816): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  816): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  816): evaluateTrafficStatsPolling
,I/CLocInfoService(  816): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/WifiStateMachine(  816): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1269): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1269): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1269): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1269): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1269): First Scan Start
,I/wpa_supplicant( 1269): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  816): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  816): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  816): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,I/Hs20UtilService( 1301): Starting #6
,D/WifiP2pService(  816): InactiveState{ what=143375 }
,I/Hs20UtilService( 1301): Message received 5007
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService(  816): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/EntConnectivity(  816): Not allowed due to - mEnabled false
D/ConnectivityService(  816): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  816): calling update connectivity
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  816): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  816): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  816): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  816): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1481): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  277): Clearing all IP addresses on wlan0
D/CSLegacyTypeTracker(  816): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  816): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  816): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  816): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  816): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/SmartBondingService(  816): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/SmartBondingService(  816): getSBEnabled() enabled =false
V/NetworkStats(  816): updateIfacesLocked()
,V/NetworkStats(  816): performPollLocked(flags=0x1)
D/ConnectivityService(  816): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkStatsFactory(  816): UpdateStatsForKnox
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  816): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
,D/NtpTrustedTime(  816): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): updateDataNetType()
,D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
V/NetworkStats(  816): performPollLocked() took 5ms
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
,D/NtpTrustedTime(  816): currentTimeMillis() cache hit
V/NetworkStats(  816): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
,D/WifiStateMachine(  816): updateConfiguredNetworkExpiration - currTime: 1452237978653
D/WifiStateMachine(  816): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/WifiTrafficPoller(  816): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/CLocInfoService(  816): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
E/WifiStateMachine(  816): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  816): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNetworkAgent(  816): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  816): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  816): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  816): setDetailed state send new extra info"NG700"
,D/NtpTrustedTime(  816): currentTimeMillis() cache hit
,D/NtpTrustedTime(  816): currentTimeMillis() cache hit
,D/SecContentProvider2(  816): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  816): mCursor = null
,I/Hs20UtilService( 1301): Starting #7
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,D/SecContentProvider2(  816): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  816): mCursor = null
,I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,I/chromium( 7465): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1481): FileWriteThread : threadType = 3
,D/ConnectivityService(  816): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  816): updateDataUsageMap
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2196): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SystemBroadcastReceiver( 7180): [#DCM#] [DCM_Performance] onReceive completed in time  7055 microsec. 
,D/SmartBondingService(  816): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  816): MasterInitialState.processMessage what=3
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  816): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  816): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  816): CLoinfo wifi false
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  816): getNetworkEnabled : wifi : true mobile : true
,W/SLocation(  816): No Active Data Connection
,I/DBG_DM  ( 3819): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/NetworkMonitor( 5410): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 6801): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6801): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6801): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6801): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6801): noConnectivity : true
,I/DBG_DM  ( 3819): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 7180): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7180): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7180): [#DCM#] setIsConnectedForExtractors 
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7607): MountEmulatedStorage()
,E/Zygote  ( 7607): v2
I/libpersona( 7607): KNOX_SDCARD checking this for 10002
I/libpersona( 7607): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7607 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 281us total 14.382ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 244us total 7.692ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 8.646ms
,D/TimaKeyStoreProvider( 7607): TimaSignature is unavailable
,D/ActivityThread( 7607): Added TimaKeyStore provider
,D/ResourcesManager( 7607): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  816): Killing 6645:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7626): MountEmulatedStorage()
E/Zygote  ( 7626): v2
I/libpersona( 7626): KNOX_SDCARD checking this for 1000
I/libpersona( 7626): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7626 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7626): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  816): failed to open /acct/uid_1000/pid_6645/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7626): TimaSignature is unavailable
,D/ActivityThread( 7626): Added TimaKeyStore provider
,D/ResourcesManager( 7626): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/PowerManagerService(  816): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  816): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  816): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  816): lcd : 3 +
,D/lights  (  816): lcd : 3 -
,D/lights  (  816): lcd : 1 +
D/DisplayPowerController(  816): getFinalBrightness : 1 -> 1
,D/lights  (  816): lcd : 1 -
,D/DisplayPowerController(  816): getFinalBrightness : 1 -> 1
,I/DIAGMON_AGENT( 7626): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7626): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7626): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7626): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7626): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7626): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1269): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1269): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1269): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1269): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1269): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  816): [1,452,237,979,672 ms] noteScanEnd no scan source
,E/WifiStateMachine(  816): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@20e80f2d sup_state=SCANNING debouncing=false
,I/CLocInfoService(  816): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  816): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  816): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  816): setDetailed state send new extra info0x
,D/SecContentProvider2(  816): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  816): mCursor = null
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1269): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1269): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1269): Associated with C0.AA.48
,E/WifiStateMachine(  816): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  816): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  816): uri = 20 selection = getPromptCredentialsEnabled
,E/Zygote  ( 7648): MountEmulatedStorage()
,E/Zygote  ( 7648): v2
I/libpersona( 7648): KNOX_SDCARD checking this for 10011
I/ActivityManager(  816): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7648 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 7648): KNOX_SDCARD not a persona
,D/SecContentProvider2(  816): mCursor = null
,I/SELinux ( 7648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/wpa_supplicant( 1269): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1269): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/SELinux ( 7648): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine(  816): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  816): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  816): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  816): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  816): mCursor = null
,I/wpa_supplicant( 1269): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1269): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1269): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1269): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1269): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1269): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1269): Blacklist: Clear (temp) 
I/wpa_supplicant( 1269): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  816): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  816): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  816): Network connection established
,D/WifiNative-HAL(  816): callSECApiVoid - ID [50]
,E/WifiStateMachine(  816): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/CLocInfoService(  816): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  816): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService(  816): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  816): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  816): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  816): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  816): Got NetworkAgent Messenger
D/ConnectivityService(  816): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  816): updateNetworkInfo()
D/ConnectivityService(  816): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  816): NetworkAgent connected
,E/WifiStateMachine(  816): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  816): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  816): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  816): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 7648): TimaSignature is unavailable
,D/ActivityThread( 7648): Added TimaKeyStore provider
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine(  816): Start Dhcp Watchdog 2
,D/SecContentProvider2(  816): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  816): mCursor = null
,D/ResourcesManager( 7648): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,V/AlarmManager(  816): waitForAlarm result :4
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  816): calculateWifiScore() report new score 60
,I/WifiStateMachine(  816): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  816): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/ConnectivityService(  816): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  816): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  816): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  816): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/SMD     (  282): DCD ON
,I/ActivityManager(  816): Killing 6755:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/FOTA_Client( 7648): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7648): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7648): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7648): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7648): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  816): failed to open /acct/uid_10015/pid_6755/cgroup.procs: No such file or directory
,E/WifiStateMachine(  816): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  816): do suspend false
,E/Zygote  ( 7674): MountEmulatedStorage()
E/Zygote  ( 7674): v2
I/libpersona( 7674): KNOX_SDCARD checking this for 10019
I/libpersona( 7674): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7674 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/WifiP2pService(  816): InactiveState{ what=143375 }
D/WifiP2pService(  816): P2pEnabledState{ what=143375 }
,I/ActivityManager(  816): Killing 6785:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
D/SecContentProvider2(  816): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  816): mCursor = null
,I/SELinux ( 7674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7674): TimaSignature is unavailable
,D/ActivityThread( 7674): Added TimaKeyStore provider
,W/libprocessgroup(  816): failed to open /acct/uid_10016/pid_6785/cgroup.procs: No such file or directory
,D/ResourcesManager( 7674): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7674): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452237980018
,I/KLMS-2.4.503: ( 7674): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7674): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7674): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  816): Killing 6558:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7690): MountEmulatedStorage()
E/Zygote  ( 7690): v2
I/libpersona( 7690): KNOX_SDCARD checking this for 10037
I/libpersona( 7690): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7690 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7690): TimaSignature is unavailable
,D/ActivityThread( 7690): Added TimaKeyStore provider
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  816): failed to open /acct/uid_10034/pid_6558/cgroup.procs: No such file or directory
,I/SO_AGENT( 7690): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/dhcpcd  ( 7708): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7708): version 5.5.6 starting
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/dhcpcd  ( 7708): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/SPPClientService( 5131): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6839): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6839): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6839): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6839): [SLFUCHKMGR] constructor called
,I/SA      ( 6839): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6839): [OR] == isSIMCardReady false ==
,I/SA      ( 6839): [SCU] == networkStateCheck == false
I/SA      ( 6839): [OR] onReceive END
,E/SPPClientService( 5131): [[SystemStateMonitorService]] No Active Internet
,I/ActivityManager(  816): Killing 4605:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7708): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7708): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7708): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7708): bssid match
,I/dhcpcd  ( 7708): wlan0: rebinding lease of 192.168.1.135
,E/Zygote  ( 7717): MountEmulatedStorage()
E/Zygote  ( 7717): v2
I/libpersona( 7717): KNOX_SDCARD checking this for 10071
I/libpersona( 7717): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7717 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
,D/ActivityThread( 7717): Added TimaKeyStore provider
,I/dhcpcd  ( 7708): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,D/ResourcesManager( 7717): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7717): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7717): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7717): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup(  816): failed to open /acct/uid_10035/pid_4605/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7708): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  816): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  816): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  816): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7717): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7717): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7717): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7717): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7717): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  816): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  816): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  816): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  816): selectionArgs: false
D/SettingsProvider(  816): selectionArgs: 10071
D/SecContentProvider(  816): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  816): ret = -1
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7717): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7717): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7717): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7717): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7717): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7717): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1332): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7746): MountEmulatedStorage()
E/Zygote  ( 7746): v2
I/libpersona( 7746): KNOX_SDCARD checking this for 1000
I/libpersona( 7746): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7746 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  816): Killing 6101:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7746): TimaSignature is unavailable
,D/ActivityThread( 7746): Added TimaKeyStore provider
,D/ResourcesManager( 7746): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7746): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7746): premStatus:2
,I/KnoxUsageLogPro( 7746): isEulaShown : false
,I/KnoxUsageLogPro( 7746): KnoxUsageReceiver onReceive : not Processible, just return
,W/libprocessgroup(  816): failed to open /acct/uid_10042/pid_6101/cgroup.procs: No such file or directory
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7770): MountEmulatedStorage()
,E/Zygote  ( 7770): v2
I/libpersona( 7770): KNOX_SDCARD checking this for 10088
I/libpersona( 7770): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7770 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  816): Killing 5739:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7770): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/CountryDetector(  816): No listener is left
,D/TimaKeyStoreProvider( 7770): TimaSignature is unavailable
,D/ActivityThread( 7770): Added TimaKeyStore provider
,W/libprocessgroup(  816): failed to open /acct/uid_10050/pid_5739/cgroup.procs: No such file or directory
D/ResourcesManager( 7770): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,E/WifiStateMachine(  816): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/WifiP2pService(  816): InactiveState{ what=143375 }
D/HeadsetStateMachine( 3235): Disconnected process message: 10
D/WifiP2pService(  816): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  816): WifiStateMachine DHCP successful
,E/WifiStateMachine(  816): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  816): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  816): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  816): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  816): Not connected state, yet.
,E/WifiStateMachine(  816): VerifyingLinkState enter
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  816): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  816): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  816): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  816): callSECApiInt - ID [210]
,E/WifiStateMachine(  816): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  816): updateNetworkInfo()
,D/ConnectivityService(  816): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  816): Adding iface wlan0 to network 503
,I/CLocInfoService(  816): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  816): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  816): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  816): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  816): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  816): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  816): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  816): Now, connected state.
E/WifiStateMachine(  816): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  816): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  816): evaluateTrafficStatsPolling
,I/CLocInfoService(  816): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  816): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  816): mBoosterFLAG : 0
I/WifiTrafficPoller(  816): current booster mode : FullMode
,D/WifiNative-HAL(  816): callSECApiVoid - ID [212]
,E/WifiStateMachine(  816): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  816): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/CLocInfoService(  816): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  816): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  816): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  816): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  816): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  816): updateSourceRoutes : add src route for:192.168.1.135
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/        (  277): QcRouteController
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  816): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/StatusBar.NetworkController( 1169): applyOpen
I/WifiStateMachine(  816): REQUEST_POWER_SAVE_ON
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,I/ActivityManager(  816): Killing 6863:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5543): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5543): getCountryCode(): countryCode = DE
,D/Headlines( 5543): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5543): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5543): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5543): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5543): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5543): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5543): requestUpdateNewsWelcomeCard !!! no welcome card
V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7807): MountEmulatedStorage()
,E/Zygote  ( 7807): v2
I/libpersona( 7807): KNOX_SDCARD checking this for 10128
I/libpersona( 7807): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7807 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/        (  277): QcRouteController
,I/SELinux ( 7807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  816): Setting Dns servers for network 503 to [/192.168.1.1]
I/SELinux ( 7807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/Nat464Xlat(  816): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  816): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  816): updateNetworkInfo()
D/ConnectivityService(  816): calling update connectivity
E/ConnectivityService(  816): updateNetworkInfo()
D/ConnectivityService(  816): ignoring duplicate network state non-change
E/SELinux ( 7807): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  816): ignoring duplicate network state non-change
D/ConnectivityService(  816): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  816): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): Connected
D/ConnectivityService(  816): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  816): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  816): Validated
D/ConnectivityService(  816):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  816):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  816):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  816): currentScore = 0, newScore = 60
D/ConnectivityService(  816):    accepting network in place of null
D/ConnectivityService(  816): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1481): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  816): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  816): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  816): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  816): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  816): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  816): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  816): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/EntConnectivity(  816): Not allowed due to - mEnabled false
D/ConnectivityService(  816): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  816): calling update connectivity
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  816): updateIfacesLocked()
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
V/NetworkStats(  816): performPollLocked(flags=0x1)
D/ConnectivityService(  816): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/NetworkStatsFactory(  816): UpdateStatsForKnox
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  816): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  816): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  816):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  816):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  816): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  816): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  816): calling update connectivity
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  816): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  816): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
D/SmartBondingService(  816): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  816): performPollLocked() took 7ms
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
V/NetworkStats(  816): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
W/libprocessgroup(  816): failed to open /acct/uid_10051/pid_6863/cgroup.procs: No such file or directory
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  816): currentTimeMillis() cache hit
D/NtpTrustedTime(  816): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/TimaKeyStoreProvider( 7807): TimaSignature is unavailable
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/ActivityThread( 7807): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/ResourcesManager( 7807): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7807): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7807): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7807): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7807): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7807): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7807): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7807): Loading: webviewchromium
,I/LibraryLoader( 7807): Time to load native libraries: 7 ms (timestamps 2089-2096)
,I/LibraryLoader( 7807): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7807): Binding Chromium to main looper Looper (main, tid 1) {2c01e8e0}
,I/LibraryLoader( 7807): Expected native library version number "",actual native library version number ""
,I/chromium( 7807): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7807): Initializing chromium process, renderers=0
,W/art     ( 7807): Attempt to remove local handle scope entry from IRT, ignoring
,D/ConnectivityService(  816): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/chromium( 7807): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7807): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7807): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,D/Tethering(  816): MasterInitialState.processMessage what=3
,D/SmartBondingService(  816): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  816): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  816): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  816): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/SmartBondingService(  816): getSBEnabled() enabled =false
D/SmartBondingService(  816): getSBEnabled() enabled =false
,I/CLocInfoService(  816): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  816): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  816): CLocinfo wifi true 
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2196): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2082): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2082): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3819): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5410): type=WIFI subType= reason=null isConnected=true
I/DBG_DM  ( 3819): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7180): [#DCM#] [DCM_Performance] onReceive completed in time  1811 microsec. 
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/AudioManagerAndroid( 7807): Requires BLUETOOTH permission
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7180): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7180): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7180): [#DCM#] setIsConnectedForExtractors 
,I/DatabaseRebuilderTask( 7180): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7180): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7180): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7180): [#DCM#] getSuccessState = true
I/FrameworkService( 7180): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7180): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Adreno-EGL( 7807): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7807): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7807): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7807): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7807): Remote Branch: 
I/Adreno-EGL( 7807): Local Patches: 
I/Adreno-EGL( 7807): Reconstruct Branch: 
,I/SystemUtils( 7180): [#DCM#] LM: false,AM:650637312
,I/DCMThreadPoolExecutor( 7180): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7180): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@3aa5f668 is submitted
I/FrameworkService( 7180): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 16565 mirosec. 
,I/DatabaseRebuilderTask( 7180): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7180): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7180): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
I/DatabaseRebuilderTask( 7180): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7180): [#DCM#] No of Location data to be added:  0
I/DatabaseRebuilderTask( 7180): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7180): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7180): [#DCM#] setHeavySharedPref set as  false
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  816): mCursor = null
,I/IntentHandler( 7180): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7180): [#DCM#] afterExecute FutureTask
,I/DCMController( 7180): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@3aa5f668
,I/NSApplication( 7807): Starting up...
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7874): MountEmulatedStorage()
I/libpersona( 7874): KNOX_SDCARD checking this for 10138
E/Zygote  ( 7874): v2
I/libpersona( 7874): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7874 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  816): Killing 6881:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  816): failed to open /acct/uid_10058/pid_6881/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7874): TimaSignature is unavailable
,D/ActivityThread( 7874): Added TimaKeyStore provider
,D/ResourcesManager( 7874): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7874): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7874): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7874): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7874): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7874): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7890): MountEmulatedStorage()
,E/Zygote  ( 7890): v2
I/libpersona( 7890): KNOX_SDCARD checking this for 10163
I/libpersona( 7890): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7890 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  816): Killing 6256:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  816): failed to open /acct/uid_1000/pid_6256/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7890): TimaSignature is unavailable
,D/ActivityThread( 7890): Added TimaKeyStore provider
,D/ConnectivityService(  816): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ResourcesManager( 7890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7890): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7890): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7916): MountEmulatedStorage()
E/Zygote  ( 7916): v2
I/libpersona( 7916): KNOX_SDCARD checking this for 10078
I/libpersona( 7916): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7916 uid=10078 gids={50078, 9997} abi=armeabi-v7a
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/art     (  312): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 416us total 18.282ms
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,I/SELinux ( 7916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 384us total 12.959ms
,E/SELinux ( 7916): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 399us total 12.363ms
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/TimaKeyStoreProvider( 7916): TimaSignature is unavailable
,D/ActivityThread( 7916): Added TimaKeyStore provider
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
D/SecurityLogAgent( 7538): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7538): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7538): StateMachine : Current State = 1
,I/ActivityManager(  816): Killing 6902:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,D/SecurityLogAgent( 7538): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,I/ActivityManager(  816): Killing 6959:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,D/com.peel.receiver.ConnectivityActionReceiver( 5646): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): last run: 1452237897227 -- System.currentTimeMillis()-last_run: 85032
D/com.peel.receiver.ConnectivityActionReceiver( 5646): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): ... skip last_72_check
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,D/ResourcesManager( 7916): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,D/BadgeProvider( 7916): onCreate
D/BadgeProvider( 7916): DatabaseHelper
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,E/Zygote  ( 7937): MountEmulatedStorage()
I/libpersona( 7937): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7937): v2
I/libpersona( 7937): KNOX_SDCARD not a persona
,I/ActivityManager(  816): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7937 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7890): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/SELinux ( 7937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7937): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7916): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7916): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7916): sendNotify, [notify] : null
D/BadgeProvider( 7916): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7916): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7916): update, [UpdateCount] : 1
,D/Launcher.Model( 1487): reloadBadges entered.
,D/TimaKeyStoreProvider( 7937): TimaSignature is unavailable
,D/ActivityThread( 7937): Added TimaKeyStore provider
,D/ResourcesManager( 7937): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  816): Killing 6935:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,W/libprocessgroup(  816): failed to open /acct/uid_10033/pid_6959/cgroup.procs: No such file or directory
,W/libprocessgroup(  816): failed to open /acct/uid_10098/pid_6902/cgroup.procs: No such file or directory
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  816): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/libprocessgroup(  816): failed to open /acct/uid_10099/pid_6935/cgroup.procs: No such file or directory
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7157): notifyNetworkActivated
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7157): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  816): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/Kids    ( 2442): [AccountUtils] Account not ready
W/Kids    ( 2442): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2442): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2442): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2442): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2442): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2442): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2442): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2442): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/Watchdog(  816): !@Sync 3
,D/hcjo    ( 7157): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7157): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7157): exit::IDLE
D/InitializeManagerStateMachine( 7157): entry::NETWORK_CHECK
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7157): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7157): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7157): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7157): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7157): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7157): entry::SUCCESS
D/hcjo    ( 7157): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1301): Starting #8
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
D/hcjo    ( 7157): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7157): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7157): exit::SUCCESS
D/InitializeManagerStateMachine( 7157): entry::IDLE
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1301): Starting #9
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #10
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #11
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  816): callSECApi what=220
D/WifiStateMachine(  816): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6801): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6801): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6801): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6801): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  816): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=816
,D/DisplayPowerController(  816): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  816): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DIAGMON_AGENT( 7626): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7626): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  816): lcd : 8 +
D/DisplayPowerController(  816): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/lights  (  816): lcd : 8 -
,D/DisplayPowerController(  816): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7648): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7648): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7648): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7648): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7648): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7674): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452237982977
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7674): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7674): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7674): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7674): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/GCM     ( 1692): Connected
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7674): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SO_AGENT( 7690): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1692): Message class com.google.f.a.a.p
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/SPPClientService( 5131): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6839): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6839): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6839): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 6839): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6839): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6839): [SCU] == networkStateCheck == true
,I/SA      ( 6839): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6839): isChinaCountryCode : false
I/SA      ( 6839): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6839): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 6839): [OR] GetMyCountryZoneTask
,I/SA      ( 6839): [OR] onReceive END
,I/SA      ( 6839): [SRS] prepareGetMyCountryZone
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 6839): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6839): [SSP] query invoked
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
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
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/art     (  816): Explicit concurrent mark sweep GC freed 72798(4MB) AllocSpace objects, 7(177KB) LOS objects, 29% free, 37MB/53MB, paused 1.731ms total 126.229ms
,D/accuweather( 7717): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7717): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6839): [TPMU] GetMccFromDB : null
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 6839): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6839): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7746): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7746): premStatus:2
,I/KnoxUsageLogPro( 7746): isEulaShown : false
I/KnoxUsageLogPro( 7746): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,E/File    ( 6839): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/Headlines( 5543): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5543): getCountryCode(): countryCode = DE
,D/Headlines( 5543): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5543): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5543): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5543): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5543): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5543): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5543): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7874): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7874): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7874): PeriphStartReceiver.onReceive - no need to start
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,D/RCPManagerService(  816): exchangeData() failure , invalid userId
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7538): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7538): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7538): StateMachine : Current State = 1
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7538): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5646): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): last run: 1452237897227 -- System.currentTimeMillis()-last_run: 86188
D/com.peel.receiver.ConnectivityActionReceiver( 5646): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5646): ... skip last_72_check
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7465): BLE is supported
I/jxcore-log( 7465): 
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2442): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7157): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7157): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7157): exit::IDLE
D/InitializeManagerStateMachine( 7157): entry::NETWORK_CHECK
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7157): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7157): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7157): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7157): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7157): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7157): entry::SUCCESS
D/hcjo    ( 7157): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7157): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7157): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7157): exit::SUCCESS
D/InitializeManagerStateMachine( 7157): entry::IDLE
,I/GCM     ( 2442): Message from null null
,E/GCM     ( 2442): Dropping message from null
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2442): [AccountUtils] Account not ready
W/Kids    ( 2442): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2442): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2442): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2442): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2442): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2442): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2442): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2442): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2442): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/SA      ( 6839): [RC New] Execute method=[GET] start
,I/SA      ( 6839): [RC New] Security=[true]
,I/System.out( 6839): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6839): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 6839): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/WifiStateMachine(  816): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  816): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7708): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7708): wlan0: sendmsg: Cannot assign requested address
,E/WifiStateMachine(  816): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  816): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
E/WifiStateMachine(  816): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  816): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  816): identical MTU - not setting
D/SmartBondingService(  816): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  816): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  816): getSBEnabled() enabled =false
,D/SmartBondingService(  816): getSBEnabled() enabled =false
,D/SmartBondingService(  816): getSBEnabled() enabled =false
,D/ConnectivityService(  816): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  816): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  277): QcRouteController
,V/        (  277): QcRouteController
,W/NetworkManagementService(  816): route cmd failed: 
W/NetworkManagementService(  816): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  816): '
W/NetworkManagementService(  816): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  816): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  816): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  816): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  816): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  816): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  816): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  816): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  816): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  816): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  816): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  816): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  816): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  816): calling update connectivity
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  816): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,D/ConnectivityService(  816): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  816): calling update connectivity
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  816):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  816): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,I/SA      ( 6839): [RC New] [v2liruge] api execute + 632
,I/SA      ( 6839): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6839): AsyncTask #1 calls detatch()
,I/SA      ( 6839): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6839): [OCP] update openData : PL
,I/SA      ( 6839): [TPMU] getNetworkMcc : 
,I/SA      ( 6839): [SCU] saveMccToPreferece Start
I/SA      ( 6839): [SCU] RegionMCC : 260
,I/SA      ( 6839): [SSP] query invoked
,I/SA      ( 6839): [TPMU] GetMccFromDB : null
,I/SA      ( 6839): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6839): [SCU] saveMccToPreferece End
,I/SA      ( 6839): [RC New] executeRequest [v2liruge] end. 715
,I/SA      ( 6839): [RC New] Execute end
,I/SA      ( 6839): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6839): [OR] GetMyCountryZoneTask Success
,D/PowerManagerService(  816): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  816): [PWL] On : 76136 (30001 ms ago)
I/PowerManagerService(  816): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,I/PowerManagerService(  816): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=816, ws=WorkSource{10059}) (elapsedTime=2631)
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
E/SMD     (  282): DCD ON
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  816): SIOP:: AP = 380, PST = 414, CUR = 300
,I/GAV4    ( 7807): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  816): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 816) eventTime = 107023
,D/PowerManagerService(  816): [s] UserActivityState : 4 -> 1
,D/PowerManagerService(  816): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=816 (0x0)
,D/PowerManagerService(  816): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=816, ws=WorkSource{10059}) (elapsedTime=3522)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
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
,D/LockPatternUtilsCache( 1169): value : false
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6801): mConnectivityHandler : connected
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6801): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6801): ================================================
,I/CSTORAGE( 6801):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6801): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6801): [GetString-S]
E/art     ( 6801): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6801): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6801): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6801): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6801): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6801): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6801): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7708): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  282): DCD ON
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!,
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 7708): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7708): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7157): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7157): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7157): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7157): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7157): RestApi Request Add : 2307
,E/File    ( 7157): fail readDirectory() errno=2
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/System.out( 7157): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 7157): (HTTPLog)-Static: isShipBuild true
,I/System.out( 7157): (HTTPLog)-Thread-1180-1002709361: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/PreloadUpdateManagerStateMachine( 7157): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/qtaguid ( 7157): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7157, getuid(): 10040
,I/qtaguid ( 7157): Untagging socket 26
,D/hcjo    ( 7157): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 7157): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 7157): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7157): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7157): entry::REQ_UPDATE_CHECK
,I/Volley  ( 7157): RestApi Request Add : 2315
,I/qtaguid ( 7157): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7157, getuid(): 10040
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/qtaguid ( 7157): Untagging socket -1
,I/qtaguid ( 7157): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 7157): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 7157): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 7157): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 7157): exit::REQ_UPDATE_CHECK
,D/PreloadUpdateManagerStateMachine( 7157): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 7157): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7157): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 7157): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 7157): entry::IDLE
,D/FactoryTest( 6519): Not factory mode
,D/FactoryTest( 6519): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6519): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6519): still no open session command from host, so toast
,W/ContextImpl( 6519): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6519): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6519): Timeline: Activity_launch_request id:com.android.settings time:115437
,E/PersonaManagerService(  816): inState():  stateMachine is null !!
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  816): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  816): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  816): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/MTPRx   ( 6519): started activity for popup
I/SQLiteSecureOpenHelper( 3578): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3578): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager( 6519): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6519): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6519): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6519): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6519): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6519): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6519): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6519): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6519): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/ActivityManager(  816): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  816): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  816): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@751e905 attribute=null, token = android.os.BinderProxy@396b03c4
,I/SQLiteSecureOpenHelper( 3578): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3578): getDatabaseLocked(b,b,pwd)...
,E/SMD     (  282): DCD ON
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6519): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6519): dev.kiessupport is : TRUE
,D/Activity( 6519): performCreate Call secproduct feature valuefalse
I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,D/Activity( 6519): performCreate Call debug elastic valuetrue
I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  816): post active user change for 0
,D/KnoxTimeoutHandler(  816): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  816): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7465): Timeline: Activity_idle id: android.os.BinderProxy@36f54a77 time:115681
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  816): SIOP:: AP = 340, PST = 402, CUR = 300
,D/X       (  816): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/SystemBroadcastReceiver( 7180): [#DCM#] [DCM_Performance] onReceive completed in time  1422 microsec. 
,D/ContentApp( 1221):  LEVEL : -1
,I/SystemBroadcastReceiver( 7180): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7180): [#DCM#] onReceive action = EVENT_SIOP
,E/TranscodeReceiver( 7246): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7246):  SIOP_LEVEL: -1
,V/AlarmManager(  816): waitForAlarm result :4
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 26838(1590KB) AllocSpace objects, 17(1377KB) LOS objects, 40% free, 17MB/29MB, paused 464us total 30.419ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6690): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6690): [1] 5.onFinished: Scheduling replication attempt 3.
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/CustomFrequencyManagerService(  816): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  816): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  816): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  pkgName : ACTIVITY_RESUME_BOOSTER@10
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/CustomFrequencyManagerService(  816): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 816  tag : ACTIVITY_RESUME_BOOSTER@10
,V/AlarmManager(  816): waitForAlarm result :4,
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  816): SIOP:: AP = 330, PST = 388, CUR = 300
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  282): DCD ON
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/PowerManagerService(  816): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  816): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  816): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  816): lcd : 6 +
,D/lights  (  816): lcd : 6 -
,D/lights  (  816): lcd : 1 +
,D/DisplayPowerController(  816): getFinalBrightness : 1 -> 1
,D/lights  (  816): lcd : 1 -
,D/DisplayPowerController(  816): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/Watchdog(  816): !@Sync 4
,E/SMD     (  282): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  816): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  816): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/SSRM:m  (  816): SIOP:: AP = 320, PST = 372, CUR = 300
,D/PowerManagerService(  816): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  816): Nap time (uid 1000)...
I/PowerManagerService(  816): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  816): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  816): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  816): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  816): setDeviceInteractive: 0
,D/PowerManagerService(  816): handleSandman : startDream()
,D/InputManager-JNI(  816): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  816): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  816): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  816): Sleeping (uid 1000)...
D/PowerManagerService(  816): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  816): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  816): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  816): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  816): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  816): 	.unregisterCallback : 1, client=
D/SContextService(  816): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@27197b9, Service = Auto Rotation, used = 1
,W/CAE     (  816): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  816): stop(ContextProvider.java:149)
,V/CAE     (  816): clear(AutoRotationRunner.java:182)
,V/CAE     (  816): disable(AutoRotationRunner.java:171)
,I/CAE     (  816): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  816): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  298): sendContextData: -78, 7, 0, 0
,D/CAE     (  816): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  816): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  816): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  816): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  816): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  816): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  816): removeSContextService() : service = Auto Rotation
D/SContextService(  816): ===== SContext Service List =====
D/SContextManager(  816):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@27920d5, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3578): getWritableDatabase(pwd)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): timeout : 5000
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SQLiteSecureOpenHelper( 3578): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/DisplayPowerController(  816): ColorFade: onAnimationStart
,D/DisplayPowerController(  816): getFinalBrightness : 8 -> 0
,D/LightsService(  816): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 816) 
D/LightsService(  816): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  816): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager(  816): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DisplayPowerController(  816): getFinalBrightness : 8 -> 0
D/lights  (  816): lcd : 0 +
,D/SensorManager(  816): unregisterListener ::   
D/BatteryService(  816): turn on LED for fully charged
,I/CAE     (  816): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  816): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  816): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  816): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  298): sendContextData: -76, 13, -46, 0
,I/CAE     (  816): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 7, 26, 56,
D/lights  (  816): lcd : 0 -
D/SensorHubManager(  816): SendSensorHubData: send data = -63, 14, 7, 26, 56
D/lights  (  816): led_pattern : 5 +
D/Sensorhubs(  298): sendContextData: -63, 14, 7, 26, 56
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/lights  (  816): led_pattern : 5 -
,D/LightsService(  816): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/MotionRecognitionService(  816):  handler : SCREEN_OFF end 
,D/NotificationService(  816): ACTION_SCREEN_OFF
D/LightsService(  816): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 816) 
D/LightsService(  816): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  816): [SvcLED]  onSensorChanged::light value = 3
D/WifiStateMachine(  816): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  816): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  816): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  816): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  816): do suspend true
,D/SensorManager(  816): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  816): unregisterListener ::   
D/LightsService(  816): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  289): adev_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: enter: screen_state=off
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  289): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  816): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  816): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  816): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  816): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler(  816): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1463): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 2196): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2196): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2196): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  816): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  816): waitForAlarm result :4
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/DisplayPowerState(  816): !@ ColorFade entry
,D/DisplayPowerController(  816): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  816): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  816): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  816): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  816): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  816): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,W/ActivityManager(  816): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  816): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SensorManager(  816): unregisterListener ::   
,E/Sensors (  816): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,I/SystemBroadcastReceiver( 7180): [#DCM#] [DCM_Performance] onReceive completed in time  248 microsec. 
,I/SystemBroadcastReceiver( 7180): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7180): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7180): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  816): [PWL] sb release: PowerManagerService.Broadcasts
,D/SensorManager(  816): unregisterListener ::   
,D/DisplayPowerController(  816): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  816): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
I/DisplayManagerService(  816): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
V/ActivityManager(  816): Display changed displayId=0
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4291, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  816): stay LED for fully charged
,D/SSRM:m  (  816): SIOP:: AP = 320, PST = 360, CUR = 300
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  270): 
,I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  816): Excessive delay in setPowerMode(): 253ms
D/PowerManagerService(  816): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  816): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  816): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  816): Got set_interactive hint
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/PowerManagerService(  816): [PWL] Off : 0s ago,
I/ServiceManager(  329): Waiting for service AtCmdFwd...
I/PowerManagerService(  816): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  816): [PWL]     mDisplayReady : false
D/DisplayPowerController(  816): getFinalBrightness : 0 -> 0
D/PowerManagerService(  816): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  816): [PWL] sb release: PowerManagerService.Display
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6690): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6690): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  816): waitForAlarm result :8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  816): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  816): [PWL] Off : 5s ago
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 310, PST = 351, CUR = 300,
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  816): stay LED for fully charged
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6663): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at dsf.a(PG:807)
E/HttpOperation( 6663): 	at fhk.a(PG:1126)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 8 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 10 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6663): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at ieo.a(PG:43)
E/HttpOperation( 6663): 	at iep.a(PG:93)
E/HttpOperation( 6663): 	at fhn.a(PG:59)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/ExperimentLoader( 6663): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): 	at kfv.a(PG:65)
E/ExperimentLoader( 6663): 	at kff.u(PG:385)
E/ExperimentLoader( 6663): 	at kfb.a(PG:29)
E/ExperimentLoader( 6663): 	at kff.l(PG:132)
E/ExperimentLoader( 6663): 	at ieo.a(PG:43)
E/ExperimentLoader( 6663): 	at iep.a(PG:93)
E/ExperimentLoader( 6663): 	at fhn.a(PG:59)
E/ExperimentLoader( 6663): 	at lex.a(PG:85)
E/ExperimentLoader( 6663): 	at lex.b(PG:132)
E/ExperimentLoader( 6663): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6663): 	at fhk.a(PG:908)
E/ExperimentLoader( 6663): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6663): 	at ihi.a(PG:22)
E/ExperimentLoader( 6663): 	at kft.a(PG:91)
E/ExperimentLoader( 6663): 	at kfv.a(PG:62)
E/ExperimentLoader( 6663): 	... 12 more
E/ExperimentLoader( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6663): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6663): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6663): 	at ihi.a(PG:19)
E/ExperimentLoader( 6663): 	... 14 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6663): [getaccountstatus] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at ixd.a(PG:248)
E/HttpOperation( 6663): 	at ixd.b(PG:206)
E/HttpOperation( 6663): 	at ixd.a(PG:175)
E/HttpOperation( 6663): 	at fig.a(PG:78)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/EsSyncAdapterService( 6663): Sync failure
E/EsSyncAdapterService( 6663): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6663): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6663): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6663): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6663): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6663): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6663): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6663): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6663): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6663): 	... 10 more
E/EsSyncAdapterService( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6663): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6663): 	... 12 more
E/EsSyncAdapterService( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6663): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6663): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6663): 	... 14 more
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 123084, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  816): mCursor = null
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  816): [PWL] Off : 15s ago
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  816): SIOP:: AP = 310, PST = 342, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  816): waitForAlarm result :4
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6690): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6690): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryService(  816): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  816): !@Sync 5
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 300, PST = 332, CUR = 300
,I/PowerManagerService(  816): [PWL] Off : 30s ago
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 300, PST = 327, CUR = 300
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/VacuumService( 1692): Vacuum at: now=1452238057961 tag=VacuumService
,I/GoogleURLConnFactory( 1692): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/System.out( 1692): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1692): (HTTPLog)-Static: isShipBuild true
I/System.out( 1692): (HTTPLog)-Thread-207-691420632: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,I/qtaguid ( 1692): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,I/art     (  816): Explicit concurrent mark sweep GC freed 69089(3MB) AllocSpace objects, 36(3MB) LOS objects, 29% free, 38MB/54MB, paused 2.095ms total 174.571ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1692): No account for auth token provided
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6690): [1] 5.onFinished: Installation state replication failed.
W/Uploader( 1692):  no longer exists, so no auth token.
,D/Finsky  ( 6690): [1] 5.onFinished: Giving up after 6 failures.
,I/qtaguid ( 1692): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1692, getuid(): 10012
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7388): Starting books sync, d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6997818547312245963&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6997818547312245963&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,E/SMD     (  282): DCD ON
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6997818547312245963&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/BooksSync( 7388): Soft error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6997818547312245963&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7388): Sync error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6997818547312245963&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7388): Finished books sync
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157182, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  816): mCursor = null
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at dsf.a(PG:807)
E/HttpOperation( 6663): 	at fhk.a(PG:1126)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 8 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at ieo.a(PG:43)
E/HttpOperation( 6663): 	at iep.a(PG:93)
E/HttpOperation( 6663): 	at fhn.a(PG:59)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/ExperimentLoader( 6663): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): 	at kfv.a(PG:65)
E/ExperimentLoader( 6663): 	at kff.u(PG:385)
E/ExperimentLoader( 6663): 	at kfb.a(PG:29)
E/ExperimentLoader( 6663): 	at kff.l(PG:132)
E/ExperimentLoader( 6663): 	at ieo.a(PG:43)
E/ExperimentLoader( 6663): 	at iep.a(PG:93)
E/ExperimentLoader( 6663): 	at fhn.a(PG:59)
E/ExperimentLoader( 6663): 	at lex.a(PG:85)
E/ExperimentLoader( 6663): 	at lex.b(PG:132)
E/ExperimentLoader( 6663): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6663): 	at fhk.a(PG:908)
E/ExperimentLoader( 6663): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6663): 	at ihi.a(PG:22)
E/ExperimentLoader( 6663): 	at kft.a(PG:91)
E/ExperimentLoader( 6663): 	at kfv.a(PG:62)
E/ExperimentLoader( 6663): 	... 12 more
E/ExperimentLoader( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6663): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6663): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6663): 	at ihi.a(PG:19)
E/ExperimentLoader( 6663): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6663): [getaccountstatus] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at ixd.a(PG:248)
E/HttpOperation( 6663): 	at ixd.b(PG:206)
E/HttpOperation( 6663): 	at ixd.a(PG:175)
E/HttpOperation( 6663): 	at fig.a(PG:78)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/EsSyncAdapterService( 6663): Sync failure
E/EsSyncAdapterService( 6663): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6663): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6663): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6663): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6663): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6663): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6663): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6663): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6663): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6663): 	... 10 more
E/EsSyncAdapterService( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6663): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6663): 	... 12 more
E/EsSyncAdapterService( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6663): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6663): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6663): 	... 14 more
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 182186, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 49681(2MB) AllocSpace objects, 63(4MB) LOS objects, 40% free, 18MB/30MB, paused 2.438ms total 143.237ms
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  816): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  816): [PWL] Off : 50s ago
,D/SSRM:m  (  816): SIOP:: AP = 300, PST = 321, CUR = 300
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  816): !@Sync 6
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 312, CUR = 300
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 307, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  816): [PWL] Off : 75s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 303, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/Watchdog(  816): !@Sync 7
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7388): Starting books sync, d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5979955766552589283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  816): [PWL] Off : 105s ago
,I/PowerManagerService(  816): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  816): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  816): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=816, ws=WorkSource{10082}) (elapsedTime=760),
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5979955766552589283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  282): DCD ON
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5979955766552589283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7388): Soft error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5979955766552589283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7388): Sync error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5979955766552589283&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7388): Finished books sync
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 217714, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  816): Explicit concurrent mark sweep GC freed 43633(2MB) AllocSpace objects, 30(1065KB) LOS objects, 29% free, 37MB/53MB, paused 1.447ms total 140.854ms
D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  816): mCursor = null
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 295, CUR = 300
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  816): !@Sync 8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  816): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at dsf.a(PG:807)
E/HttpOperation( 6663): 	at fhk.a(PG:1126)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 8 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 10 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at ieo.a(PG:43)
E/HttpOperation( 6663): 	at iep.a(PG:93)
E/HttpOperation( 6663): 	at fhn.a(PG:59)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/ExperimentLoader( 6663): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): 	at kfv.a(PG:65)
E/ExperimentLoader( 6663): 	at kff.u(PG:385)
E/ExperimentLoader( 6663): 	at kfb.a(PG:29)
E/ExperimentLoader( 6663): 	at kff.l(PG:132)
E/ExperimentLoader( 6663): 	at ieo.a(PG:43)
E/ExperimentLoader( 6663): 	at iep.a(PG:93)
E/ExperimentLoader( 6663): 	at fhn.a(PG:59)
E/ExperimentLoader( 6663): 	at lex.a(PG:85)
E/ExperimentLoader( 6663): 	at lex.b(PG:132)
E/ExperimentLoader( 6663): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6663): 	at fhk.a(PG:908)
E/ExperimentLoader( 6663): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6663): 	at ihi.a(PG:22)
E/ExperimentLoader( 6663): 	at kft.a(PG:91)
E/ExperimentLoader( 6663): 	at kfv.a(PG:62)
E/ExperimentLoader( 6663): 	... 12 more
E/ExperimentLoader( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6663): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6663): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6663): 	at ihi.a(PG:19)
E/ExperimentLoader( 6663): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [getaccountstatus] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at ixd.a(PG:248)
E/HttpOperation( 6663): 	at ixd.b(PG:206)
E/HttpOperation( 6663): 	at ixd.a(PG:175)
E/HttpOperation( 6663): 	at fig.a(PG:78)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/EsSyncAdapterService( 6663): Sync failure
E/EsSyncAdapterService( 6663): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6663): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6663): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6663): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6663): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6663): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6663): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6663): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6663): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6663): 	... 10 more
E/EsSyncAdapterService( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6663): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6663): 	... 12 more
E/EsSyncAdapterService( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6663): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6663): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6663): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PanelView( 1169): There is/are notification(s) 
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 247158, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  816): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  816): [PWL] Off : 140s ago
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  816): !@Sync 9
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  816): stay LED for fully charged
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  816): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  816): TimaServiceHandler.handleMessage what =1
,D/TimaService(  816): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  816): initializing...
,I/TLC_TIMA_PKM_initialize(  816): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  816): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  816): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  816): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  816): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  816): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  816): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  816): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  816): App is not loaded in QSEE
,D/QSEECOMAPI: (  816): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  816): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  816): Trustlet response is completed
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  816): !@Sync 10
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  816): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  816): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  816): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  816): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  816): [PWL] Off : 180s ago
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :8
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  816): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): stay LED for fully charged
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7388): Starting books sync, d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4960995188234250561&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  816): waitForAlarm result :4
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  816): checkUser: useridlist=null, currentuser=0,
,I/ActivityManager(  816): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8249 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8249): MountEmulatedStorage()
,E/Zygote  ( 8249): v2
,I/libpersona( 8249): KNOX_SDCARD checking this for 10081
,I/libpersona( 8249): KNOX_SDCARD not a persona
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 8249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8249): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,D/TimaKeyStoreProvider( 8249): TimaSignature is unavailable
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/PanelView( 1169): There is/are notification(s) 
E/HttpHelper( 7388): null auth token
D/PanelView( 1169): There is/are notification(s) 
D/ActivityThread( 8249): Added TimaKeyStore provider
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,D/ResourcesManager( 8249): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4960995188234250561&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): ,	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4960995188234250561&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7388): Soft error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4960995188234250561&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7388): Sync error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4960995188234250561&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7388): Finished books sync
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  816): Killing 7003:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309810, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  816): mCursor = null
,W/libprocessgroup(  816): failed to open /acct/uid_10020/pid_7003/cgroup.procs: No such file or directory
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7465): Connected to the server!
I/jxcore-log( 7465): 
,I/chromium( 7465): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  816): !@Sync 11
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6690): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6690): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6690): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6690): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6690): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6690): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6690): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6690): Ignoring header User-Agent because its value was null.
,I/System.out( 6690): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6690): (HTTPLog)-Static: isShipBuild true
I/System.out( 6690): (HTTPLog)-Thread-1088-211284984: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  816): [PWL] Off : 225s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  816): !@Sync 12
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/MotionRecognitionService(  816): Plugged
,D/BatteryService(  816): stay LED for fully charged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  816): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6663): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at dsf.a(PG:807)
E/HttpOperation( 6663): 	at fhk.a(PG:1126)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 8 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 10 more
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SMD     (  282): DCD ON
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at ieo.a(PG:43)
E/HttpOperation( 6663): 	at iep.a(PG:93)
E/HttpOperation( 6663): 	at fhn.a(PG:59)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/ExperimentLoader( 6663): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): 	at kfv.a(PG:65)
E/ExperimentLoader( 6663): 	at kff.u(PG:385)
E/ExperimentLoader( 6663): 	at kfb.a(PG:29)
E/ExperimentLoader( 6663): 	at kff.l(PG:132)
E/ExperimentLoader( 6663): 	at ieo.a(PG:43)
E/ExperimentLoader( 6663): 	at iep.a(PG:93)
E/ExperimentLoader( 6663): 	at fhn.a(PG:59)
E/ExperimentLoader( 6663): 	at lex.a(PG:85)
E/ExperimentLoader( 6663): 	at lex.b(PG:132)
E/ExperimentLoader( 6663): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6663): 	at fhk.a(PG:908)
E/ExperimentLoader( 6663): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6663): 	at ihi.a(PG:22)
E/ExperimentLoader( 6663): 	at kft.a(PG:91)
E/ExperimentLoader( 6663): 	at kfv.a(PG:62)
E/ExperimentLoader( 6663): 	... 12 more
E/ExperimentLoader( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6663): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6663): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6663): 	at ihi.a(PG:19)
E/ExperimentLoader( 6663): 	... 14 more
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [getaccountstatus] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at ixd.a(PG:248)
E/HttpOperation( 6663): 	at ixd.b(PG:206)
E/HttpOperation( 6663): 	at ixd.a(PG:175)
E/HttpOperation( 6663): 	at fig.a(PG:78)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/EsSyncAdapterService( 6663): Sync failure
E/EsSyncAdapterService( 6663): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6663): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6663): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6663): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6663): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6663): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6663): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6663): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6663): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6663): 	... 10 more
E/EsSyncAdapterService( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6663): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6663): 	... 12 more
E/EsSyncAdapterService( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6663): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6663): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6663): 	... 14 more
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 393808, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2848): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2848): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     (  816): Explicit concurrent mark sweep GC freed 50508(3MB) AllocSpace objects, 60(1610KB) LOS objects, 29% free, 37MB/53MB, paused 1.879ms total 164.883ms
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  816): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  816): !@Sync 13
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:m  (  816): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  816): [PWL] Off : 275s ago
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 287, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  816): !@Sync 14
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 285, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :8
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 283, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 7465): --- start :testFindPeers.js---
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): testFindPeers created [object Object]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): serverPort is 8876
I/jxcore-log( 7465): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7465): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7465): initialize: My bluetooth address is B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7465): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7465): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7465): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7465): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7465): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7465): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7465): bindListen(), new LocalSocket 
D/BluetoothSocket( 7465): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7465): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a3b7bf2
,D/BluetoothSocket( 7465): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7465): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7465): start: OK
I/io.jxcore.node.ConnectionHelper( 7465): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7465): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7465): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): start: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7465): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7465): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  816): InactiveState{ what=139292 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139292 }
D/WifiP2pService(  816): P2pEnabledState add service
,D/WifiP2pService(  816): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): start: Starting P2P device discovery...
,D/WifiP2pService(  816): InactiveState{ what=139265 }
D/WifiP2pService(  816): P2pEnabledState{ what=139265 }
D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  816): callSECApi what=74
D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  816): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7465): start: OK
,I/jxcore-log( 7465): StartBroadcasting started ok
I/jxcore-log( 7465): 
,I/io.jxcore.node.ConnectionHelper( 7465): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7465): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 7465): onDiscoveryManagerStateChanged: RUNNING
,I/chromium( 7465): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1269): P2P-FIND-STOPPED 
I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  816): InactiveState{ what=147493 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  816): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): setState: RESTARTING
,D/WifiP2pService(  816): InactiveState{ what=139268 }
,I/wpa_supplicant( 1269): P2P-FIND-STOPPED 
,D/WifiP2pService(  816): InactiveState{ what=147493 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147493 }
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState add service request
,D/WifiP2pManager( 7465): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 281, CUR = 300
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
,D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 7465): 
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): Start timer timeout, starting now...
,D/WifiP2pService(  816): InactiveState{ what=139265 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139265 }
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): setState: STARTED
,D/WifiP2pService(  816): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/Watchdog(  816): !@Sync 15
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): stay LED for fully charged
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7388): Starting books sync, d
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 38180(2MB) AllocSpace objects, 29(2MB) LOS objects, 39% free, 18MB/30MB, paused 855us total 107.789ms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
E/BooksAccountManager( 7388): Authentication error,
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3412326075184662046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3412326075184662046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7388): Authentication error
E/BooksAccountManager( 7388): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7388): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7388): null auth token
,I/qtaguid ( 7388): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7388, getuid(): 10082
,I/PowerManagerService(  816): [PWL] Off : 330s ago
,I/PowerManagerService(  816): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  816): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  816): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=816, ws=WorkSource{10082}) (elapsedTime=3006),
,I/qtaguid ( 7388): Untagging socket 34
,W/ApiaryClient( 7388): Error response from books API: {
W/ApiaryClient( 7388):  "error": {
W/ApiaryClient( 7388):   "errors": [
W/ApiaryClient( 7388):    {
W/ApiaryClient( 7388):     "domain": "global",
W/ApiaryClient( 7388):     "reason": "required",
W/ApiaryClient( 7388):     "message": "Login Required",
W/ApiaryClient( 7388):     "locationType": "header",
W/ApiaryClient( 7388):     "location": "Authorization"
W/ApiaryClient( 7388):    }
W/ApiaryClient( 7388):   ],
W/ApiaryClient( 7388):   "code": 401,
W/ApiaryClient( 7388):   "message": "Login Required"
W/ApiaryClient( 7388):  }
W/ApiaryClient( 7388): }
,W/ApiaryClient( 7388): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3412326075184662046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7388): Headers suppressed
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/BooksSync( 7388): Soft error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3412326075184662046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7388): Sync error
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7388): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3412326075184662046&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7388): Headers suppressed
E/BooksSync( 7388): 
E/BooksSync( 7388): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7388): Finished books sync
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 464458, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2848): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState clear service request
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState add service request
,D/WifiP2pManager( 7465): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,D/ResourcesManager( 2848): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  816): mCursor = null
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  816): SIOP:: AP = 280, PST = 280, CUR = 300
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,E/SMD     (  282): DCD ON
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 7465): 
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7465): 
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
,D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
D/WifiP2pService(  816): P2pEnabledState clear service request
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState add service request
,D/WifiP2pManager( 7465): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7465): 
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
D/WifiP2pService(  816): P2pEnabledState clear service request
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState add service request
D/WifiP2pManager( 7465): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,E/Watchdog(  816): !@Sync 16
,E/SMD     (  282): DCD ON
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7465): 
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  816): stay LED for fully charged
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  816): !@Sync 17
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,I/PowerManagerService(  816): [PWL] Off : 390s ago
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService(  816): InactiveState{ what=139307 }
D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
D/WifiP2pService(  816): P2pEnabledState clear service request
I/ServiceManager(  329): Waiting for service AtCmdFwd...
D/WifiP2pService(  816): InactiveState{ what=139301 }
D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
D/WifiP2pService(  816): P2pEnabledState add service request
D/WifiP2pManager( 7465): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 7465): 
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7465): 
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService(  816): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
D/WifiP2pService(  816): P2pEnabledState clear service request
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
D/WifiP2pService(  816): P2pEnabledState add service request
,D/WifiP2pManager( 7465): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 7465): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/jxcore-log( 7465): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7465): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
,D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState clear service request
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState add service request
,D/WifiP2pManager( 7465): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  816): !@Sync 18
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7465): timeout now
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): weAreDoneNow
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): done, now sending data to server
I/jxcore-log( 7465): 
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
,D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState clear service request
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState add service request
,D/WifiP2pManager( 7465): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,D/WifiService(  816): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  816): callSECApi what=74
,D/WifiStateMachine(  816): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  816): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1269): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service discovery started successfully
,I/wpa_supplicant( 1269): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1269): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService(  816): InactiveState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  816): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 7465): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 7465): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 270, CUR = 300
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/WifiDisplayController(  816): Received list of peers.
,D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  816): InactiveState{ what=139283 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  816): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): restart: Restarting...
,D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
D/WifiP2pService(  816): P2pEnabledState clear service request
,D/WifiP2pService(  816): InactiveState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  816): P2pEnabledState add service request
D/WifiP2pManager( 7465): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service request added successfully
,I/jxcore-log( 7465): teardown
I/jxcore-log( 7465): 
,I/jxcore-log( 7465): testFindPeers stopped
I/jxcore-log( 7465): 
,I/io.jxcore.node.ConnectionHelper( 7465): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7465): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7465): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7465): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7465): shutdown
,D/BluetoothSocket( 7465): close() in, this: android.bluetooth.BluetoothSocket@a81653e, channel: 6, state: LISTENING
,D/BluetoothSocket( 7465): close() this: android.bluetooth.BluetoothSocket@a81653e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a3b7bf2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31e52f9fmSocket: android.net.LocalSocket@711e8ec impl:android.net.LocalSocketImpl@a2044b5 fd:FileDescriptor[152]
,D/BluetoothSocket( 7465): Closing mSocket: android.net.LocalSocket@711e8ec impl:android.net.LocalSocketImpl@a2044b5 fd:FileDescriptor[152]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7465): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7465): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7465): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7465): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7465): stop: Stopping services
,D/WifiP2pService(  816): InactiveState{ what=139298 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  816): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): stop: Stopping P2P device discovery...
,D/WifiP2pService(  816): InactiveState{ what=139268 }
,I/wpa_supplicant( 1269): P2P-FIND-STOPPED 
,D/WifiP2pService(  816): InactiveState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): stopWifiPeerDiscovery: Stopped
D/WifiP2pService(  816): P2pEnabledState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7465): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7465): release: The given listener does not exist in the list
,D/WifiP2pService(  816): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7465): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7465): setState: NOT_STARTED
,D/WifiP2pService(  816): InactiveState{ what=139307 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139307 }
,I/jxcore-log( 7465): StopBroadcasting went ok
I/jxcore-log( 7465): 
,D/WifiP2pService(  816): P2pEnabledState clear service request
,D/WifiP2pService(  816): remove channel information from framework
,I/io.jxcore.node.ConnectionHelper( 7465): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7465): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7465): P2P device discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 7465): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Service requests cleared successfully
,I/chromium( 7465): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1269): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  816): InactiveState{ what=147477 }
,D/WifiP2pService(  816): P2pEnabledState{ what=147477 }
D/WifiDisplayController(  816): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService(  816): InactiveState{ what=139283 }
D/WifiP2pService(  816): P2pEnabledState{ what=139283 }
D/WifiP2pService(  816): DefaultState{ what=139283 }
D/WifiDisplayController(  816): Received list of peers.
D/WifiDisplayController(  816):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  816):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  816):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  282): DCD ON
,D/WifiP2pService(  816): InactiveState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  816): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7465): Failed to start the service discovery, got error code: 3
,I/jxcore-log( 7465): teardown
I/jxcore-log( 7465): 
,E/jxcore  ( 7465): Error!: self.currentTest is null
E/jxcore  ( 7465): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"169","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:169:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 7465): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,I/Atfwd_Daemon(  329): Stop the daemon....
,E/Watchdog(  816): !@Sync 19
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 270, CUR = 300
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/PowerManagerService(  816): [PWL] Off : 455s ago
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  282): DCD ON
,D/TimaService(  816): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  816): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  816): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  816): !@Sync 20
,E/SMD     (  282): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  816): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  816): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  816): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  816): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,D/BatteryService(  816): stay LED for fully charged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON,
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 280, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
,I/MotionRecognitionService(  816): setPowerConnected  = true
,D/BatteryService(  816): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,W/ContextImpl(  816): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  282): DCD ON
,I/ActivityManager(  816): Killing 7010:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,W/libprocessgroup(  816): failed to open /acct/uid_10003/pid_7010/cgroup.procs: No such file or directory
,V/AlarmManager(  816): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1692): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6663): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at dsf.a(PG:807)
E/HttpOperation( 6663): 	at fhk.a(PG:1126)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 8 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 10 more
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
D/SecContentProvider2(  816): mCursor = null
,D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at kff.l(PG:132)
E/HttpOperation( 6663): 	at ieo.a(PG:43)
E/HttpOperation( 6663): 	at iep.a(PG:93)
E/HttpOperation( 6663): 	at fhn.a(PG:59)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/ExperimentLoader( 6663): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6663): 	at kfv.a(PG:65)
E/ExperimentLoader( 6663): 	at kff.u(PG:385)
E/ExperimentLoader( 6663): 	at kfb.a(PG:29)
E/ExperimentLoader( 6663): 	at kff.l(PG:132)
E/ExperimentLoader( 6663): 	at ieo.a(PG:43)
E/ExperimentLoader( 6663): 	at iep.a(PG:93)
E/ExperimentLoader( 6663): 	at fhn.a(PG:59)
E/ExperimentLoader( 6663): 	at lex.a(PG:85)
E/ExperimentLoader( 6663): 	at lex.b(PG:132)
E/ExperimentLoader( 6663): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6663): 	at fhk.a(PG:908)
E/ExperimentLoader( 6663): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6663): 	at ihi.a(PG:22)
E/ExperimentLoader( 6663): 	at kft.a(PG:91)
E/ExperimentLoader( 6663): 	at kfv.a(PG:62)
E/ExperimentLoader( 6663): 	... 12 more
E/ExperimentLoader( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6663): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6663): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6663): 	at ihi.a(PG:19)
E/ExperimentLoader( 6663): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1692): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  816): uri = 14 selection = getSealedState
,D/SecContentProvider2(  816): mCursor = null
D/SecContentProvider2(  816): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  816): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  816): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6663): [getaccountstatus] Unexpected exception
E/HttpOperation( 6663): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6663): 	at kfv.a(PG:65)
E/HttpOperation( 6663): 	at kff.u(PG:385)
E/HttpOperation( 6663): 	at kfb.a(PG:29)
E/HttpOperation( 6663): 	at ixd.a(PG:248)
E/HttpOperation( 6663): 	at ixd.b(PG:206)
E/HttpOperation( 6663): 	at ixd.a(PG:175)
E/HttpOperation( 6663): 	at fig.a(PG:78)
E/HttpOperation( 6663): 	at lex.a(PG:85)
E/HttpOperation( 6663): 	at lex.b(PG:132)
E/HttpOperation( 6663): 	at fhk.a(PG:1146)
E/HttpOperation( 6663): 	at fhk.a(PG:908)
E/HttpOperation( 6663): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6663): 	at ihi.a(PG:22)
E/HttpOperation( 6663): 	at kft.a(PG:91)
E/HttpOperation( 6663): 	at kfv.a(PG:62)
E/HttpOperation( 6663): 	... 12 more
E/HttpOperation( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6663): 	at gde.c(Unknown Source)
E/HttpOperation( 6663): 	at gde.b(Unknown Source)
E/HttpOperation( 6663): 	at ihi.a(PG:19)
E/HttpOperation( 6663): 	... 14 more
,E/EsSyncAdapterService( 6663): Sync failure
E/EsSyncAdapterService( 6663): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6663): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6663): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6663): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6663): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6663): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6663): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6663): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6663): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6663): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6663): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6663): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6663): 	... 10 more
E/EsSyncAdapterService( 6663): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6663): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6663): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6663): 	... 12 more
E/EsSyncAdapterService( 6663): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6663): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6663): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6663): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6663): 	... 14 more
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/SMD     (  282): DCD ON
D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  816): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 636661, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  816): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  816): mCursor = null
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  816): !@Sync 21
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  816): [PWL] Off : 525s ago
,E/SMD     (  282): DCD ON
,V/AlarmManager(  816): waitForAlarm result :4
,D/ConnectivityService(  816): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  816): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  816): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  816): stay LED for fully charged
D/BatteryService(  816): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  816):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  816): Plugged
I/MotionRecognitionService(  816): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3235): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3235): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  282): DCD ON
,D/SSRM:m  (  816): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  282): DCD ON
,E/Watchdog(  816): !@Sync 22
,E/SMD     (  282): DCD ON

```
