#### Test 5065027857de7f1_thali07_samsung-SM-G900F Logs


```
--------- beginning of main,
V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7361): null auth token
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
I/qtaguid ( 7361): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
I/qtaguid ( 7361): Untagging socket 34
W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
W/ApiaryClient( 7361): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7065400473248065720&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
--------- beginning of system
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SMD     (  285): DCD ON
D/AndroidRuntime( 7415): 
D/AndroidRuntime( 7415): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7415): CheckJNI is OFF
D/AndroidRuntime( 7415): setted country_code = Germany
D/AndroidRuntime( 7415): setted countryiso_code = DE
D/AndroidRuntime( 7415): setted sales_code = DBT
D/AndroidRuntime( 7415): readGMSProperty: start
D/AndroidRuntime( 7415): readGMSProperty: already setted!!
D/AndroidRuntime( 7415): readGMSProperty: end
D/AndroidRuntime( 7415): addProductProperty: start
E/AffinityControl( 7415): AffinityControl: registerfunction enter
D/AndroidRuntime( 7415): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  907): inState():  stateMachine is null !!
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  907): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  907): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  907): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SQLiteSecureOpenHelper( 3554): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3554): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/AndroidRuntime( 7415): Shutting down VM
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 23
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  907): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 907) 
D/LightsService(  907): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  907): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  907): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1172): Icon Only
D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3834): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/WindowManager(  907): showStatusBarByNotification() mOpenByNotification=false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3834): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
E/Zygote  ( 7437): MountEmulatedStorage()
E/Zygote  ( 7437): v2
I/libpersona( 7437): KNOX_SDCARD checking this for 10367
I/libpersona( 7437): KNOX_SDCARD not a persona
D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7437 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7437): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1172): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@10050d92
D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/TimaKeyStoreProvider( 7437): TimaSignature is unavailable
D/ActivityThread( 7437): Added TimaKeyStore provider
V/ActivityManager(  907): Display changed displayId=0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager( 7437): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
I/WebViewFactory( 7437): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7437): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7361): null auth token
I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/LibraryLoader( 7437): Loading: webviewchromium
I/PhoneStatusBar( 1172): Icon Only
I/LibraryLoader( 7437): Time to load native libraries: 2 ms (timestamps 5711-5713)
I/LibraryLoader( 7437): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/WebViewChromiumFactoryProvider( 7437): Binding Chromium to main looper Looper (main, tid 1) {114411a7}
I/LibraryLoader( 7437): Expected native library version number "",actual native library version number ""
I/chromium( 7437): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7437): Initializing chromium process, renderers=0
W/art     ( 7437): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7437): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7437): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7437): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Adreno-EGL( 7437): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7437): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7437): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7437): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7437): Remote Branch: 
I/Adreno-EGL( 7437): Local Patches: 
I/Adreno-EGL( 7437): Reconstruct Branch: 
I/qtaguid ( 7361): Untagging socket 34
W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
W/ApiaryClient( 7361): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7065400473248065720&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7437): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7437): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/art     ( 7437): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7437): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SystemWebViewEngine( 7437): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/art     ( 7437): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7437): Attempt to remove local handle scope entry from IRT, ignoring
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
D/Activity( 7437): performCreate Call secproduct feature valuefalse
D/Activity( 7437): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/OpenGLRenderer( 7437): Render dirty regions requested: true
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/ActivityManager(  907): post active user change for 0
D/KnoxTimeoutHandler(  907): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  907): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
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
I/OpenGLRenderer( 7437): Initialized EGL, version 1.4
I/OpenGLRenderer( 7437): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7437): Enabling debug mode 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/InputMethodManagerService(  907): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +656ms
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/Adreno-ES20( 7437): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7437): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Timeline( 7437): Timeline: Activity_idle id: android.os.BinderProxy@3003b916 time:96151
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
D/JsMessageQueue( 7437): Set native->JS mode to OnlineEventsBridgeMode
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/chromium( 7437): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7437): 
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
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/CustomFrequencyManagerService(  907): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  907): mDVFSHelper.release()
I/Timeline(  907): Timeline: Activity_windows_visible id: ActivityRecord{8b9733f u0 com.test.thalitest/.MainActivity t12} time:96323
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/CustomFrequencyManagerService(  907): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
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
,D/jxcore_app_log( 7437): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359593600
,D/JX-Cordova( 7437): jxcore cordova android initializing
,D/CustomFrequencyManagerService(  907): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  tag : ACTIVITY_RESUME_BOOSTER@10
,E/BooksSync( 7361): Soft error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7065400473248065720&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7361): Sync error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7065400473248065720&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7361): Finished books sync
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  907): Killing 6349:com.google.android.talk/u0a117 (adj 15): bgCount ##41
D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 67526, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,W/libprocessgroup(  907): failed to open /acct/uid_10117/pid_6349/cgroup.procs: No such file or directory
,D/PowerManagerService(  907): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1172 (0x0)
,W/ProcessCpuTracker(  907): Skipping unknown process pid 7427
,W/ProcessCpuTracker(  907): Skipping unknown process pid 7430
,W/ProcessCpuTracker(  907): Skipping unknown process pid 7432
W/ProcessCpuTracker(  907): Skipping unknown process pid 7433
,W/ProcessCpuTracker(  907): Skipping unknown process pid 7435
,W/ProcessCpuTracker(  907): Skipping unknown process pid 7453
W/ProcessCpuTracker(  907): Skipping unknown process pid 7490
,I/art     (  907): Explicit concurrent mark sweep GC freed 28068(1454KB) AllocSpace objects, 9(1814KB) LOS objects, 29% free, 37MB/53MB, paused 1.245ms total 82.897ms
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/GAV2    ( 7361): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  907): waitForAlarm result :4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 380, PST = 428, CUR = 300
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/jxcore-log( 7437): Initializing JXcore engine
,W/jxcore-log( 7437): JXcore engine is ready
,W/jxcore-log( 7437): Starting JXcore engine
,E/auditd  ( 2131): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  907): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  907): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7509): MountEmulatedStorage()
E/Zygote  ( 7509): v2
I/libpersona( 7509): KNOX_SDCARD checking this for 1000
I/libpersona( 7509): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7509 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7509): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7509): TimaSignature is unavailable
,D/ActivityThread( 7509): Added TimaKeyStore provider
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 7437): Platform android
W/jxcore-log( 7437): 
W/jxcore-log( 7437): Process ARCH arm
W/jxcore-log( 7437): 
,D/ResourcesManager( 7509): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecurityLogAgent( 7509):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7509):  SeDenialReceiver : File path = null
D/Finsky  ( 6711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6711): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  907): Killing 6609:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,W/libprocessgroup(  907): failed to open /acct/uid_10075/pid_6609/cgroup.procs: No such file or directory
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,I/jxcore-log( 7437): JXcore Cordova bridge is ready!
I/jxcore-log( 7437): 
W/jxcore-log( 7437): JXcore engine is started
,D/TaskPersister(  907): removeObsoleteFile: deleting file=11_task_thumbnail.png
,I/jxcore-log( 7437): Toggling radios to true
I/jxcore-log( 7437): 
,D/BluetoothAdapter( 7437): enable()
,D/BluetoothAdapter( 7437): enable(): BT is already enabled..!
,D/WifiService(  907): New client listening to asynchronous messages
,I/WifiManager( 7437): packageName : com.test.thalitest
,D/SecContentProvider(  907): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  907): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  907): mCursor = null
,D/WifiService(  907): setWifiEnabled: true pid=7437, uid=10367
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  907): Permission Denial: getCurrentUser() from pid=7437, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  907): Failed getting userId using ActivityManagerNative
W/WifiService(  907): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7437, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  907): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  907): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  907): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  907): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  907): name = wifi_on
,I/WifiService(  907): disconnect: pid=7437, uid=10367
,I/wpa_supplicant( 1319): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7437): Radios toggled
I/jxcore-log( 7437): 
I/jxcore-log( 7437): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7437): 
I/jxcore-log( 7437): Perf Test app loaded loaded
I/jxcore-log( 7437): 
I/chromium( 7437): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 7437): check test folder
I/jxcore-log( 7437): 
,I/jxcore-log( 7437): found test : ./testFindPeers.js
I/jxcore-log( 7437): 
,I/wpa_supplicant( 1319): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1319): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1319): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1319): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  907): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1319): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1319): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1319): Disconnected - do not scan
I/wpa_supplicant( 1319): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  907): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  907): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  907): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  907): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 7437): found test : ./testSendData.js
I/jxcore-log( 7437): 
,E/WifiStateMachine(  907): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  907): InactiveState{ what=143375 }
D/WifiP2pService(  907): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1702): Read error: ssl=0xaf037e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1702): SSL shutdown failed: ssl=0xaf037e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  907): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  907): updateNetworkInfo()
,D/ConnectivityService(  907): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  907): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiConfigStore(  907): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Validated
I/WifiTrafficPoller(  907): evaluateTrafficStatsPolling
,I/CLocInfoService(  907): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/WifiStateMachine(  907): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1319): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1319): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1319): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1319): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1319): First Scan Start
,I/wpa_supplicant( 1319): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine(  907): ConnectModeState: Network connection lost 
,I/Hs20UtilService( 1301): Starting #6
,E/WifiStateMachine(  907): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
I/Hs20UtilService( 1301): Message received 5007
,E/WifiStateMachine(  907): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  907): InactiveState{ what=143375 }
D/WifiP2pService(  907): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  907): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  907): calling update connectivity
,E/WifiStateMachine(  907): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  907): Not allowed due to - mEnabled false
D/ConnectivityService(  907): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Disconnected - quitting
D/Nat464Xlat(  907): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/WifiStateMachine(  907): updateConfiguredNetworkExpiration - currTime: 1449832301262
D/WifiStateMachine(  907): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
,I/WifiTrafficPoller(  907): evaluateTrafficStatsPolling
,I/CLocInfoService(  907): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  907): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  907): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService(  907): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  907): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  907): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  907): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/CSLegacyTypeTracker(  907): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  907): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1468): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  907): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  907): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  907): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  907): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  907): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
,D/SmartBondingService(  907): getSBEnabled() enabled =false
,V/NetworkStats(  907): updateIfacesLocked()
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
V/NetworkStats(  907): performPollLocked(flags=0x1)
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
D/NetworkStatsFactory(  907): UpdateStatsForKnox
E/WifiStateMachine(  907): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  907): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  907): getNetworkEnabled : wifi : true mobile : true
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
V/NetworkStats(  907): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
E/WifiStateMachine(  907): setDetailed state send new extra info"NG700"
,E/ConnectivityService(  907): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/SecContentProvider2(  907): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  907): mCursor = null
E/ConnectivityService(  907): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/Choreographer( 7437): Skipped 73 frames!  The application may be doing too much work on its main thread.
,V/NetworkStats(  907): performPollLocked() took 13ms
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
I/Hs20UtilService( 1301): Starting #7
,I/Hs20UtilService( 1301): Message received 5007
,D/SecContentProvider2(  907): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  907): mCursor = null
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,I/chromium( 7437): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1468): FileWriteThread : threadType = 3
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  907): updateDataUsageMap
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2182): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  907): MasterInitialState.processMessage what=3
,D/SmartBondingService(  907): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  907): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  907): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  907): CLoinfo wifi false
,D/SmartBondingService(  907): getNetworkEnabled : wifi : true mobile : true
,I/DBG_DM  ( 3834): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,W/SLocation(  907): No Active Data Connection
,I/SystemBroadcastReceiver( 7197): [#DCM#] [DCM_Performance] onReceive completed in time  4148 microsec. 
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7197): [#DCM#] Calling notifyListeners. 
I/DCMController( 7197): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5410): type=WIFI subType= reason=null isConnected=false
I/DCMController( 7197): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3834): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 6819): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6819): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6819): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6819): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6819): noConnectivity : true
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7578): MountEmulatedStorage()
,E/Zygote  ( 7578): v2
I/libpersona( 7578): KNOX_SDCARD checking this for 10002
I/libpersona( 7578): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7578 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 419us total 15.986ms
,I/SELinux ( 7578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 392us total 11.104ms
,I/SELinux ( 7578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7578): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 14MB/23MB, paused 399us total 11.834ms
,D/TimaKeyStoreProvider( 7578): TimaSignature is unavailable
,D/ActivityThread( 7578): Added TimaKeyStore provider
,E/SMD     (  285): DCD ON
,D/ResourcesManager( 7578): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  907): Killing 6625:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7596): MountEmulatedStorage()
E/Zygote  ( 7596): v2
I/libpersona( 7596): KNOX_SDCARD checking this for 1000
I/libpersona( 7596): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7596 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_6625/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7596): TimaSignature is unavailable
,D/ActivityThread( 7596): Added TimaKeyStore provider
,D/ResourcesManager( 7596): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7596): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7596): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/PowerManagerService(  907): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  907): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  907): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  907): lcd : 49 +
,D/lights  (  907): lcd : 49 -
,I/wpa_supplicant( 1319): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 1319): wlan0: Setting scan request: 8 sec 0 usec
,D/lights  (  907): lcd : 41 +
,I/wpa_supplicant( 1319): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1319): wlan0: State: SCANNING -> ASSOCIATING
,E/WifiStateMachine(  907): [1,449,832,302,312 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1319): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/lights  (  907): lcd : 41 -
,E/WifiStateMachine(  907): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@29181f77 sup_state=SCANNING debouncing=false
,D/lights  (  907): lcd : 33 +
,I/CLocInfoService(  907): External Intent Received android.net.wifi.SCAN_RESULTS
,D/lights  (  907): lcd : 33 -
,E/WifiStateMachine(  907): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  907): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  907): setDetailed state send new extra info0x
,D/SecContentProvider2(  907): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  907): mCursor = null
,D/lights  (  907): lcd : 24 +
,D/lights  (  907): lcd : 24 -
,D/lights  (  907): lcd : 16 +
,D/lights  (  907): lcd : 16 -
,D/DisplayPowerController(  907): getFinalBrightness : 15 -> 15
D/lights  (  907): lcd : 15 +
,D/lights  (  907): lcd : 15 -
,D/DisplayPowerController(  907): getFinalBrightness : 15 -> 15
,I/DIAGMON_AGENT( 7596): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/wpa_supplicant( 1319): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1319): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1319): Associated with C0.AA.48
,E/WifiStateMachine(  907): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  907): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/DIAGMON_AGENT( 7596): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7596): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2(  907): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  907): mCursor = null
I/DIAGMON_AGENT( 7596): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1319): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1319): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  907): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  907): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  907): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  907): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  907): mCursor = null
,I/wpa_supplicant( 1319): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1319): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1319): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1319): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1319): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1319): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1319): Blacklist: Clear (temp) 
I/wpa_supplicant( 1319): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  907): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  907): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  907): Network connection established
,D/WifiNative-HAL(  907): callSECApiVoid - ID [50]
,E/WifiStateMachine(  907): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/CLocInfoService(  907): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  907): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  907): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  907): Got NetworkAgent Messenger
D/ConnectivityService(  907): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  907): updateNetworkInfo()
D/ConnectivityService(  907): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  907): NetworkAgent connected
E/WifiStateMachine(  907): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  907): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  907): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  907): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  907): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  907): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  907): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine(  907): Start Dhcp Watchdog 2
,D/SecContentProvider2(  907): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  907): mCursor = null
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  907): calculateWifiScore() report new score 60
,I/WifiStateMachine(  907): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  907): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  907): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  907): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  907): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  907): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/Zygote  ( 7620): MountEmulatedStorage()
,E/Zygote  ( 7620): v2
I/libpersona( 7620): KNOX_SDCARD checking this for 10011
I/libpersona( 7620): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7620 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7620): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7620): TimaSignature is unavailable
,D/ActivityThread( 7620): Added TimaKeyStore provider
,D/ResourcesManager( 7620): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/WifiStateMachine(  907): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  907): do suspend false
,D/SecContentProvider2(  907): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  907): InactiveState{ what=143375 }
D/WifiP2pService(  907): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  907): mCursor = null
,I/ActivityManager(  907): Killing 6666:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7620): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7620): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7620): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7620): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7620): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7635): MountEmulatedStorage()
I/ActivityManager(  907): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7635 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7635): v2
I/ActivityManager(  907): Killing 6778:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
I/libpersona( 7635): KNOX_SDCARD checking this for 10019
I/libpersona( 7635): KNOX_SDCARD not a persona
,I/SELinux ( 7635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7635): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_6666/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7635): TimaSignature is unavailable
,D/ActivityThread( 7635): Added TimaKeyStore provider
,W/libprocessgroup(  907): failed to open /acct/uid_10015/pid_6778/cgroup.procs: No such file or directory
,D/ResourcesManager( 7635): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7635): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7635): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449832302732
,I/KLMS-2.4.503: ( 7635): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7635): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7635): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  907): Killing 6801:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7654): MountEmulatedStorage()
E/Zygote  ( 7654): v2
I/libpersona( 7654): KNOX_SDCARD checking this for 10037
I/libpersona( 7654): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7654 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7661): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7661): version 5.5.6 starting
,E/dhcpcd  ( 7661): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10016/pid_6801/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7654): TimaSignature is unavailable
,D/ActivityThread( 7654): Added TimaKeyStore provider
,D/ResourcesManager( 7654): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/dhcpcd  ( 7661): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7661): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7661): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7661): bssid match
,I/dhcpcd  ( 7661): wlan0: rebinding lease of 192.168.1.135
,I/SO_AGENT( 7654): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5218): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6860): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6860): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6860): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6860): [SLFUCHKMGR] constructor called
,I/SA      ( 6860): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6860): [OR] == isSIMCardReady false ==
,I/SA      ( 6860): [SCU] == networkStateCheck == false
I/SA      ( 6860): [OR] onReceive END
,E/SPPClientService( 5218): [[SystemStateMonitorService]] No Active Internet
,I/ActivityManager(  907): Killing 6583:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7679): MountEmulatedStorage()
E/Zygote  ( 7679): v2
I/libpersona( 7679): KNOX_SDCARD checking this for 10071
I/libpersona( 7679): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7679 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  907): failed to open /acct/uid_10034/pid_6583/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7679): TimaSignature is unavailable
,D/ActivityThread( 7679): Added TimaKeyStore provider
,D/ResourcesManager( 7679): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7679): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7679): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7679): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7679): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7679): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7679): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7679): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7679): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7679): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7679): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7679): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  907): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  907): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  907): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  907): selectionArgs: false
D/SettingsProvider(  907): selectionArgs: 10071
D/SecContentProvider(  907): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  907): ret = -1
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7679): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7679): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7679): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7679): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
D/accuweather( 7679): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 7679): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7679): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7679): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1327): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7679): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
D/accuweather( 7679): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7696): MountEmulatedStorage()
I/libpersona( 7696): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7696): v2
I/libpersona( 7696): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7696 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  907): Killing 4652:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7696): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7696): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7696): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7696): TimaSignature is unavailable
,D/ActivityThread( 7696): Added TimaKeyStore provider
,W/libprocessgroup(  907): failed to open /acct/uid_10035/pid_4652/cgroup.procs: No such file or directory
,D/ResourcesManager( 7696): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7696): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7696): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7696): premStatus:2
,I/KnoxUsageLogPro( 7696): isEulaShown : false
,I/KnoxUsageLogPro( 7696): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7714): MountEmulatedStorage()
E/Zygote  ( 7714): v2
I/libpersona( 7714): KNOX_SDCARD checking this for 10088
I/libpersona( 7714): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7714 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  907): Killing 6116:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7714): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7714): TimaSignature is unavailable
,D/ActivityThread( 7714): Added TimaKeyStore provider
,D/ResourcesManager( 7714): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  907): failed to open /acct/uid_10042/pid_6116/cgroup.procs: No such file or directory
,I/ActivityManager(  907): Killing 5751:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/Headlines( 5549): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5549): getCountryCode(): countryCode = DE
,D/Headlines( 5549): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5549): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5549): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5549): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5549): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5549): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5549): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7730): MountEmulatedStorage()
I/libpersona( 7730): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7730): v2
I/libpersona( 7730): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7730 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CountryDetector(  907): No listener is left
,I/SELinux ( 7730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7730): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7730): TimaSignature is unavailable
,D/ActivityThread( 7730): Added TimaKeyStore provider
,D/ResourcesManager( 7730): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  907): failed to open /acct/uid_10050/pid_5751/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 7730): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7730): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7730): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7730): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7730): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7730): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7730): Loading: webviewchromium
,I/LibraryLoader( 7730): Time to load native libraries: 6 ms (timestamps 2539-2545)
,I/LibraryLoader( 7730): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7730): Binding Chromium to main looper Looper (main, tid 1) {2a223bbd}
,I/LibraryLoader( 7730): Expected native library version number "",actual native library version number ""
,I/chromium( 7730): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7730): Initializing chromium process, renderers=0
,W/art     ( 7730): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7730): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7730): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7730): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7730): Requires BLUETOOTH permission
,I/Adreno-EGL( 7730): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7730): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7730): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7730): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7730): Remote Branch: 
I/Adreno-EGL( 7730): Local Patches: 
I/Adreno-EGL( 7730): Reconstruct Branch: 
,I/NSApplication( 7730): Starting up...
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7785): MountEmulatedStorage()
I/libpersona( 7785): KNOX_SDCARD checking this for 10138
E/Zygote  ( 7785): v2
I/libpersona( 7785): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7785 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  907): Killing 6881:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7785): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7785): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7785): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7785): TimaSignature is unavailable
,D/ActivityThread( 7785): Added TimaKeyStore provider
,D/ResourcesManager( 7785): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7785): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7785): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7785): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  907): failed to open /acct/uid_10051/pid_6881/cgroup.procs: No such file or directory
,D/QuickConnect( 7785): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7785): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7785): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7661): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,E/Zygote  ( 7808): MountEmulatedStorage()
,E/Zygote  ( 7808): v2
I/libpersona( 7808): KNOX_SDCARD checking this for 10163
I/libpersona( 7808): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7808 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  907): Killing 6898:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/dhcpcd  ( 7661): wlan0: leased 192.168.1.135 for 86400 seconds
,I/SELinux ( 7808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/WifiStateMachine(  907): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  907): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ConnectivityService(  907): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/TimaKeyStoreProvider( 7808): TimaSignature is unavailable
D/ActivityThread( 7808): Added TimaKeyStore provider
,W/libprocessgroup(  907): failed to open /acct/uid_10058/pid_6898/cgroup.procs: No such file or directory
,D/ResourcesManager( 7808): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7808): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7808): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7808): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7808): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
,E/Zygote  ( 7851): MountEmulatedStorage()
E/Zygote  ( 7851): v2
I/libpersona( 7851): KNOX_SDCARD checking this for 10078
I/libpersona( 7851): KNOX_SDCARD not a persona
,I/ActivityManager(  907): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7851 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/art     (  312): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 279us total 12.281ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 8.453ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.691ms
,E/WifiStateMachine(  907): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,I/SELinux ( 7851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,E/SELinux ( 7851): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/WifiP2pService(  907): InactiveState{ what=143375 }
D/WifiP2pService(  907): P2pEnabledState{ what=143375 }
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
E/WifiStateMachine(  907): WifiStateMachine DHCP successful
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
E/WifiStateMachine(  907): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  907): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  907): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
E/WifiStateMachine(  907): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  907): Not connected state, yet.
E/WifiStateMachine(  907): VerifyingLinkState enter
,D/WifiStateMachine(  907): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  907): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  907): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  907): callSECApiInt - ID [210]
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  907): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService(  907): updateNetworkInfo()
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
D/ConnectivityService(  907): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  907): Adding iface wlan0 to network 503
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,I/CLocInfoService(  907): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  907): updateDnsLinkProperty: enter
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
D/WifiWatchdogStateMachine.DnsPinger(  907): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  907): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  907): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  907): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,E/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  907): Now, connected state.
E/WifiStateMachine(  907): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  907): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  907): evaluateTrafficStatsPolling
,I/CLocInfoService(  907): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  907): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  907): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  907): mBoosterFLAG : 0
I/WifiTrafficPoller(  907): current booster mode : FullMode
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/WifiNative-HAL(  907): callSECApiVoid - ID [212]
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
D/TimaKeyStoreProvider( 7851): TimaSignature is unavailable
,D/ConnectivityService(  907): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine(  907): ConnectedState Enter  mScreenOn=true scanperiod=20000
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
D/ConnectivityService(  907): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  907): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
D/ActivityThread( 7851): Added TimaKeyStore provider
E/ConnectivityService(  907): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  907): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  907): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  279): QcRouteController
,I/CLocInfoService(  907): External Intent Received android.net.wifi.STATE_CHANGE
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,I/WifiStateMachine(  907): REQUEST_POWER_SAVE_ON
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,I/ActivityManager(  907): Killing 6266:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/        (  279): QcRouteController
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/ResourcesManager( 7851): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,V/        (  279): QcRouteController
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7509): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7509): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7509): StateMachine : Current State = 1
,D/SecurityLogAgent( 7509): StateMachine : Changed Current State = 1
,I/ActivityManager(  907): Killing 6919:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,V/        (  279): QcRouteController
,D/com.peel.receiver.ConnectivityActionReceiver( 5653): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
V/        (  279): QcRouteController
,D/com.peel.receiver.ConnectivityActionReceiver( 5653): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): last run: 1449794886030 -- System.currentTimeMillis()-last_run: 37418480
D/com.peel.receiver.ConnectivityActionReceiver( 5653): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): ... skip last_72_check
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,D/BadgeProvider( 7851): onCreate
,D/BadgeProvider( 7851): DatabaseHelper
,V/        (  279): QcRouteController
,V/        (  279): QcRouteController
,E/Zygote  ( 7886): MountEmulatedStorage()
E/Zygote  ( 7886): v2
I/libpersona( 7886): KNOX_SDCARD checking this for 10178
I/libpersona( 7886): KNOX_SDCARD not a persona
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,I/ActivityManager(  907): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7886 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/        (  279): QcRouteController
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,I/SELinux ( 7886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,E/SELinux ( 7886): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_6266/cgroup.procs: No such file or directory
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ConnectivityService(  907): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  907): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  907): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907): calling update connectivity
D/ConnectivityService(  907): ignoring duplicate network state non-change
E/ConnectivityService(  907): updateNetworkInfo()
D/ConnectivityService(  907): ignoring duplicate network state non-change
,E/ConnectivityService(  907): updateNetworkInfo()
D/ConnectivityService(  907): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  907): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907): calling update connectivity
D/ConnectivityService(  907): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  907):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  907): Validated
D/ConnectivityService(  907):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  907):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907): currentScore = 0, newScore = 60
D/ConnectivityService(  907):    accepting network in place of null
,D/ConnectivityService(  907): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1468): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BadgeProvider( 7851): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/CSLegacyTypeTracker(  907): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  907): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  907): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EntConnectivity(  907): Not allowed due to - mEnabled false
D/ConnectivityService(  907): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907): calling update connectivity
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  907): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  907): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  907):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  907): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  907): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907): calling update connectivity
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  907): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/SmartBondingService(  907): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  907): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
,V/NetworkStats(  907): updateIfacesLocked()
,V/NetworkStats(  907): performPollLocked(flags=0x1)
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  907): UpdateStatsForKnox
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  907): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,V/NetworkStats(  907): performPollLocked() took 4ms
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
W/libprocessgroup(  907): failed to open /acct/uid_10098/pid_6919/cgroup.procs: No such file or directory
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
V/NetworkStats(  907): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/TimaKeyStoreProvider( 7886): TimaSignature is unavailable
D/ActivityThread( 7886): Added TimaKeyStore provider
,V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
V/BitmapFactory( 7808): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7886): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/Launcher.Model( 1490): reloadBadges entered.
,D/BadgeProvider( 7851): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7851): sendNotify, [notify] : null
D/BadgeProvider( 7851): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7851): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7851): update, [UpdateCount] : 1
,I/ActivityManager(  907): Killing 6976:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2415): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  907): failed to open /acct/uid_10033/pid_6976/cgroup.procs: No such file or directory
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2415): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7172): notifyNetworkActivated
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7172): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  907): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
W/ActivityManager(  907): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2415): [AccountUtils] Account not ready
W/Kids    ( 2415): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2415): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2415): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2415): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2415): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/hcjo    ( 7172): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7172): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7172): exit::IDLE
D/InitializeManagerStateMachine( 7172): entry::NETWORK_CHECK
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7172): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7172): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7172): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7172): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 7172): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7172): entry::SUCCESS
I/Hs20UtilService( 1301): Starting #8
D/hcjo    ( 7172): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/hcjo    ( 7172): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7172): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/InitializeManagerStateMachine( 7172): exit::SUCCESS
D/InitializeManagerStateMachine( 7172): entry::IDLE
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #9
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #10
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #11
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  907): callSECApi what=220
D/WifiStateMachine(  907): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PowerManagerService(  907): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=907
,D/DisplayPowerController(  907): getFinalBrightness : 54 -> 54
,D/PowerManagerService(  907): [s] DisplayPowerCallbacks : onStateChanged()
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
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  907): lcd : 22 +
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  907): lcd : 22 -
,D/lights  (  907): lcd : 30 +
,D/lights  (  907): lcd : 30 -
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  907): lcd : 38 +
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  907): lcd : 38 -
,D/lights  (  907): lcd : 46 +
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/SMD     (  285): DCD ON
,D/lights  (  907): lcd : 46 -
,D/DisplayPowerController(  907): getFinalBrightness : 54 -> 54
,D/lights  (  907): lcd : 54 +
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  907): lcd : 54 -
,D/DisplayPowerController(  907): getFinalBrightness : 54 -> 54
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  907): MasterInitialState.processMessage what=3
,D/SmartBondingService(  907): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  907): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  907): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2182): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  907): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
,I/CLocInfoService(  907): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  907): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  907): CLocinfo wifi true 
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2206): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2206): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7197): [#DCM#] [DCM_Performance] onReceive completed in time  388 microsec. 
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): value : false
,I/SystemBroadcastReceiver( 7197): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7197): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7197): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3834): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3834): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor( 5410): type=WIFI subType= reason=null isConnected=true
,I/DatabaseRebuilderTask( 7197): [#DCM#] postDBrebuildIntent rebuildLocation =  true
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 6819): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6819): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6819): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6819): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7197): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7197): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7197): [#DCM#] getSuccessState = true
I/FrameworkService( 7197): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7197): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DIAGMON_AGENT( 7596): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7596): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SystemUtils( 7197): [#DCM#] LM: false,AM:677593088
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/DCMThreadPoolExecutor( 7197): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7197): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1db6f87 is submitted
,I/FrameworkService( 7197): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 67310 mirosec. 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/DatabaseRebuilderTask( 7197): [#DCM#] createLuceneReader done 
,I/DatabaseRebuilderTask( 7197): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7197): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DatabaseRebuilderTask( 7197): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7197): [#DCM#] No of Location data to be added:  0
,I/DatabaseRebuilderTask( 7197): [#DCM#] releaseLuceneReader done 
I/DatabaseRebuilderTask( 7197): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7197): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7197): [#DCM#] Stopping service with ids up to  1
,I/DCMThreadPoolExecutor( 7197): [#DCM#] afterExecute FutureTask
I/DCMController( 7197): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@1db6f87
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7620): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7620): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7620): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7620): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
I/FOTA_Client( 7620): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7635): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7635): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449832305285
,I/KLMS-2.4.503: ( 7635): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7635): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7635): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7635): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7635): StateImplV2(): networkChangeListener().END
,E/Watchdog(  907): !@Sync 3
,I/SO_AGENT( 7654): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/SPPClientService( 5218): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6860): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6860): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6860): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6860): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6860): [OR] == isSIMCardReady false ==
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6860): [SCU] == networkStateCheck == true
I/SA      ( 6860): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6860): isChinaCountryCode : false
I/SA      ( 6860): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6860): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SA      ( 6860): [OR] GetMyCountryZoneTask
,I/SA      ( 6860): [OR] onReceive END
,I/SA      ( 6860): [SRS] prepareGetMyCountryZone
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SA      ( 6860): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6860): [SSP] query invoked
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/AlarmManager(  907): waitForAlarm result :4
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     (  907): Explicit concurrent mark sweep GC freed 69651(3MB) AllocSpace objects, 7(177KB) LOS objects, 29% free, 37MB/53MB, paused 1.439ms total 114.624ms
,I/SA      ( 6860): [TPMU] GetMccFromDB : null
I/SA      ( 6860): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6860): [TPM] isNoProxy(default) : true
,D/accuweather( 7679): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7679): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7696): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7696): premStatus:2
,I/KnoxUsageLogPro( 7696): isEulaShown : false
I/KnoxUsageLogPro( 7696): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 6860): fail readDirectory() errno=2
,D/Headlines( 5549): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5549): getCountryCode(): countryCode = DE
,D/Headlines( 5549): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5549): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5549): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5549): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5549): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5549): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5549): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7785): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7785): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7785): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
D/ConnectivityService(  907): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/RCPManagerService(  907): exchangeData() failure , invalid userId
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7509): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7509): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7509): StateMachine : Current State = 1
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7509): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 5653): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
,D/com.peel.receiver.ConnectivityActionReceiver( 5653): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): last run: 1449794886030 -- System.currentTimeMillis()-last_run: 37419560
D/com.peel.receiver.ConnectivityActionReceiver( 5653): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5653): ... skip last_72_check
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2415): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2415): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7172): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7172): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7172): exit::IDLE
D/InitializeManagerStateMachine( 7172): entry::NETWORK_CHECK
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7172): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 7172): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7172): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7172): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7172): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7172): entry::SUCCESS
D/hcjo    ( 7172): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7172): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7172): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7172): exit::SUCCESS
D/InitializeManagerStateMachine( 7172): entry::IDLE
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 29588(1809KB) AllocSpace objects, 16(1296KB) LOS objects, 39% free, 18MB/30MB, paused 467us total 34.109ms
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2415): [AccountUtils] Account not ready
W/Kids    ( 2415): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2415): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2415): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2415): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2415): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2415): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2415): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1702): Connected
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1702): Message class com.google.f.a.a.p
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6860): [RC New] Execute method=[GET] start
,I/SA      ( 6860): [RC New] Security=[true]
,I/System.out( 6860): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6860): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6860): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7437): BLE supported!!
I/jxcore-log( 7437): 
,I/SA      ( 6860): [RC New] [v2liruge] api execute + 899
I/SA      ( 6860): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6860): AsyncTask #1 calls detatch()
,I/SA      ( 6860): [ODM] saveOpenData( GEO_IP, PL ),
,I/SA      ( 6860): [OCP] update openData : PL
,I/SA      ( 6860): [TPMU] getNetworkMcc : 
,I/SA      ( 6860): [SCU] saveMccToPreferece Start
,I/SA      ( 6860): [SCU] RegionMCC : 260
,I/SA      ( 6860): [SSP] query invoked
,I/SA      ( 6860): [TPMU] GetMccFromDB : null
,I/SA      ( 6860): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6860): [SCU] saveMccToPreferece End
,I/SA      ( 6860): [RC New] executeRequest [v2liruge] end. 973
,I/SA      ( 6860): [RC New] Execute end
,I/SA      ( 6860): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6860): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 7661): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7661): wlan0: sendmsg: Cannot assign requested address
,I/WifiStateMachine(  907): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  907): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SMD     (  285): DCD ON
,D/PowerManagerService(  907): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  907): [PWL] On : 76975 (30002 ms ago)
I/PowerManagerService(  907): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  907): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=907, ws=WorkSource{10059}) (elapsedTime=3368)
,E/WifiStateMachine(  907): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  907): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  907): identical MTU - not setting
,D/ConnectivityService(  907): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  907): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
D/PowerManagerService(  907): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 907) eventTime = 107103
,D/PowerManagerService(  907): [s] UserActivityState : 4 -> 1
V/        (  279): QcRouteController
E/WifiStateMachine(  907): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/PowerManagerService(  907): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=907 (0x0)
D/PowerManagerService(  907): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=907, ws=WorkSource{10059}) (elapsedTime=3498)
,D/SmartBondingService(  907): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  907): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  907): getSBEnabled() enabled =false
,D/SmartBondingService(  907): getSBEnabled() enabled =false
D/SmartBondingService(  907): getSBEnabled() enabled =false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  279): QcRouteController
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/NetworkManagementService(  907): route cmd failed: 
W/NetworkManagementService(  907): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  907): '
W/NetworkManagementService(  907): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  907): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  907): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  907): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  907): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  907): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  907): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  907): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  907): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  907): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  907): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  907): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907): calling update connectivity
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  907): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
D/ConnectivityService(  907): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  907): calling update connectivity
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  907):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  907): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/GAV4    ( 7730): Thread[GAThread,5,main]: No campaign data found.
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
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
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
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
,I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SSRM:m  (  907): SIOP:: AP = 400, PST = 426, CUR = 300
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_out.png
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6819): mConnectivityHandler : connected
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6819): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6819): ================================================
,I/CSTORAGE( 6819):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6819): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6819): [GetString-S]
E/art     ( 6819): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6819): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6819): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6819): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6819): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6819): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6819): [ensureRegistration] - No Samsung account
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  285): DCD ON
,I/dhcpcd  ( 7661): wlan0: sending IPv6 Router Solicitation
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020471/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/PreloadUpdateManagerStateMachine( 7172): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7172): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7172): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7172): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7172): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7172): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7172): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7172): entry::IDLE
,I/dhcpcd  ( 7661): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7661): wlan0: no IPv6 Routers available
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/PreloadUpdateManagerStateMachine( 7172): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7172): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7172): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7172): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7172): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7172): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7172): entry::IDLE
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/FactoryTest( 6555): Not factory mode
,D/FactoryTest( 6555): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6555): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6555): still no open session command from host, so toast
,W/ContextImpl( 6555): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6555): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6555): Timeline: Activity_launch_request id:com.android.settings time:116512
,E/PersonaManagerService(  907): inState():  stateMachine is null !!
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  907): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  907): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SQLiteSecureOpenHelper( 3554): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3554): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 6555): started activity for popup
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6555): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6555): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6555): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6555): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6555): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6555): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6555): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6555): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6555): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/ActivityManager(  907): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  907): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  907): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1344b808 attribute=null, token = android.os.BinderProxy@3f1bc6f7
,I/SQLiteSecureOpenHelper( 3554): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3554): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6555): dev.kiessupport is : TRUE
,D/Activity( 6555): performCreate Call secproduct feature valuefalse
D/Activity( 6555): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ActivityManager(  907): post active user change for 0
,D/KnoxTimeoutHandler(  907): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  907): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline( 7437): Timeline: Activity_idle id: android.os.BinderProxy@3003b916 time:116748
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/SSRM:m  (  907): SIOP:: AP = 350, PST = 414, CUR = 300
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  907): waitForAlarm result :4
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6711): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{26f06e3e u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/CustomFrequencyManagerService(  907): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  907): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  907): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/CustomFrequencyManagerService(  907): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen,
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 340, PST = 400, CUR = 300
D/X       (  907): broadcastSiopLevelIntent:: currentSiopLevel = -1
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ContentApp( 1224):  LEVEL : -1
,I/SystemBroadcastReceiver( 7197): [#DCM#] [DCM_Performance] onReceive completed in time  7618 microsec. 
,I/SystemBroadcastReceiver( 7197): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7197): [#DCM#] onReceive action = EVENT_SIOP
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7997): MountEmulatedStorage()
,E/Zygote  ( 7997): v2
I/libpersona( 7997): KNOX_SDCARD checking this for 10054
I/libpersona( 7997): KNOX_SDCARD not a persona
,I/SELinux ( 7997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  907): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7997 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
I/SELinux ( 7997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7997): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7997): TimaSignature is unavailable
,D/ActivityThread( 7997): Added TimaKeyStore provider
,D/ResourcesManager( 7997): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7997): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7997): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7997): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7997): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7997): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/TranscodeReceiver( 7997): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 7997): core_num = 4
,W/linker  ( 7997): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 7997): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 7997): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 7997): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 7997):  SIOP_LEVEL: -1
,I/ActivityManager(  907): Killing 6947:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,W/libprocessgroup(  907): failed to open /acct/uid_10099/pid_6947/cgroup.procs: No such file or directory
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4356, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  285): DCD ON
,D/PowerManagerService(  907): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  907): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  907): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  907): lcd : 53 +
,D/lights  (  907): lcd : 53 -
,D/lights  (  907): lcd : 45 +
,D/lights  (  907): lcd : 45 -
,D/lights  (  907): lcd : 36 +
,D/lights  (  907): lcd : 36 -
,D/lights  (  907): lcd : 28 +
,D/lights  (  907): lcd : 28 -
,D/lights  (  907): lcd : 20 +
,D/lights  (  907): lcd : 20 -
,D/DisplayPowerController(  907): getFinalBrightness : 15 -> 15
,D/lights  (  907): lcd : 15 +
,D/lights  (  907): lcd : 15 -
,D/DisplayPowerController(  907): getFinalBrightness : 15 -> 15
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 4
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  907): CMD_RSSI_POLL : out!
,E/SMD     (  285): DCD ON
,D/PowerManagerService(  907): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  907): Nap time (uid 1000)...
I/PowerManagerService(  907): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  907): Going to sleep due to screen timeout (uid 1000)...
D/InputManager-JNI(  907): setDeviceInteractive: 0
,D/PowerManagerService(  907): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  907): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  907): handleSandman : startDream()
,E/PowerManagerService(  907): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  907): Sleeping (uid 1000)...
D/PowerManagerService(  907): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  907): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  907): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  907): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  907): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  907): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  907): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  907): 	.unregisterCallback : 1, client=
D/SContextService(  907): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3ebe1843, Service = Auto Rotation, used = 1
W/CAE     (  907): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  907): stop(ContextProvider.java:149)
V/CAE     (  907): clear(AutoRotationRunner.java:182)
,V/CAE     (  907): disable(AutoRotationRunner.java:171)
,I/CAE     (  907): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  907): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  907): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  907): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  907): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  907): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  907): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  907): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  907): removeSContextService() : service = Auto Rotation
,D/SContextService(  907): ===== SContext Service List =====
D/SContextManager(  907):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@119a6aad, service=Auto Rotation
,D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/KeyguardViewMediator( 1172): timeout : 5000
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/DisplayPowerController(  907): ColorFade: onAnimationStart
,D/DisplayPowerController(  907): getFinalBrightness : 54 -> 0
,D/lights  (  907): lcd : 6 +
,D/lights  (  907): lcd : 6 -
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1172): handleNotifyScreenOff
,D/lights  (  907): lcd : 0 +
,D/DisplayPowerController(  907): getFinalBrightness : 54 -> 0
,D/lights  (  907): lcd : 0 -
,I/SQLiteSecureOpenHelper( 3554): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3554): getDatabaseLocked(b,b,pwd)...
,D/LightsService(  907): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 907) 
D/LightsService(  907): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  907): [SvcLED]  onSensorChanged::light value = 42
,D/SensorManager(  907): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  907): turn on LED for fully charged
,D/SensorManager(  907): unregisterListener ::   
D/lights  (  907): led_pattern : 5 +
,D/lights  (  907): led_pattern : 5 -
,D/LightsService(  907): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  907): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  907): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  907): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  907): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CAE     (  907): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 11, 12, 18,
,D/SensorHubManager(  907): SendSensorHubData: send data = -63, 14, 11, 12, 18
D/Sensorhubs(  297): sendContextData: -63, 14, 11, 12, 18
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  907):  handler : SCREEN_OFF end 
,D/NotificationService(  907): ACTION_SCREEN_OFF
D/WifiStateMachine(  907): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/LightsService(  907): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 907) 
E/WifiStateMachine(  907): handleScreenStateChanged Exit: false
D/LightsService(  907): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  907): [SvcLED]  onSensorChanged::light value = 42
,E/WifiStateMachine(  907): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  907): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  907): do suspend true
,D/SensorManager(  907): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  907): unregisterListener ::   
D/LightsService(  907): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  907): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  907): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  907): Bridge Server is not available
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1172): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  907): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  907): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1461): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1172):      ACTION_SCREEN_OFF is finished!!!! 
,D/DisplayPowerState(  907): !@ ColorFade entry
,D/DisplayPowerController(  907): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  907): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  907): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  907): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  907): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  907): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,E/StatusBar( 1172): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1172): dismissHelpPopup 
,D/SensorManager(  907): unregisterListener ::   
E/Sensors (  907): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  907): unregisterListener ::   
,D/accuweather( 2182): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2182): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2182): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerController(  907): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  907): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  907): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  907): Display changed displayId=0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ActivityManager(  907): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  907): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/SystemBroadcastReceiver( 7197): [#DCM#] [DCM_Performance] onReceive completed in time  238 microsec. 
,D/PowerManagerService(  907): [PWL] sb release: PowerManagerService.Broadcasts
I/SystemBroadcastReceiver( 7197): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7197): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7197): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/SSRM:m  (  907): SIOP:: AP = 330, PST = 384, CUR = 300
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
,I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  907): Excessive delay in setPowerMode(): 257ms
D/PowerManagerService(  907): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  907): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  907): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  907): Got set_interactive hint
,I/PowerManagerService(  907): [PWL] Off : 0s ago
I/PowerManagerService(  907): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  907): [PWL]     mDisplayReady : false
D/DisplayPowerController(  907): getFinalBrightness : 0 -> 0
D/PowerManagerService(  907): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  907): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  907): waitForAlarm result :4
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6711): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 5s ago
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 320, PST = 371, CUR = 300,
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  907): [PWL] Off : 15s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 320, PST = 362, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6681): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at dsf.a(PG:807)
E/HttpOperation( 6681): 	at fhk.a(PG:1126)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 8 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 10 more
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6681): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at ieo.a(PG:43)
E/HttpOperation( 6681): 	at iep.a(PG:93)
E/HttpOperation( 6681): 	at fhn.a(PG:59)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/ExperimentLoader( 6681): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): 	at kfv.a(PG:65)
E/ExperimentLoader( 6681): 	at kff.u(PG:385)
E/ExperimentLoader( 6681): 	at kfb.a(PG:29)
E/ExperimentLoader( 6681): 	at kff.l(PG:132)
E/ExperimentLoader( 6681): 	at ieo.a(PG:43)
E/ExperimentLoader( 6681): 	at iep.a(PG:93)
E/ExperimentLoader( 6681): 	at fhn.a(PG:59)
E/ExperimentLoader( 6681): 	at lex.a(PG:85)
E/ExperimentLoader( 6681): 	at lex.b(PG:132)
E/ExperimentLoader( 6681): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6681): 	at fhk.a(PG:908)
E/ExperimentLoader( 6681): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6681): 	at ihi.a(PG:22)
E/ExperimentLoader( 6681): 	at kft.a(PG:91)
E/ExperimentLoader( 6681): 	at kfv.a(PG:62)
E/ExperimentLoader( 6681): 	... 12 more
E/ExperimentLoader( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6681): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6681): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6681): 	at ihi.a(PG:19)
E/ExperimentLoader( 6681): 	... 14 more
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6681): [getaccountstatus] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at ixd.a(PG:248)
E/HttpOperation( 6681): 	at ixd.b(PG:206)
E/HttpOperation( 6681): 	at ixd.a(PG:175)
E/HttpOperation( 6681): 	at fig.a(PG:78)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/EsSyncAdapterService( 6681): Sync failure
E/EsSyncAdapterService( 6681): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6681): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6681): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6681): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6681): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6681): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6681): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6681): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6681): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6681): 	... 10 more
E/EsSyncAdapterService( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6681): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6681): 	... 12 more
E/EsSyncAdapterService( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6681): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6681): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6681): 	... 14 more
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 158159, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  907): mCursor = null
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  907): waitForAlarm result :4
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6711): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6711): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 310, PST = 352, CUR = 300
,I/PowerManagerService(  907): [PWL] Off : 30s ago
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 310, PST = 343, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1702): Vacuum at: now=1449832381282 tag=VacuumService
,I/GoogleURLConnFactory( 1702): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
E/Uploader( 1702): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1702): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1702): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1702): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1702): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1702): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1702): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1702): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1702): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1702): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1702): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1702): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1702): (HTTPLog)-Thread-202-617519196: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1702): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1702, getuid(): 10012
,I/qtaguid ( 1702): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1702, getuid(): 10012
,W/Uploader( 1702): No account for auth token provided
,I/qtaguid ( 1702): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1702, getuid(): 10012
,I/art     (  907): Explicit concurrent mark sweep GC freed 70871(4MB) AllocSpace objects, 34(3MB) LOS objects, 29% free, 38MB/54MB, paused 3.424ms total 249.345ms
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1702): No account for auth token provided
,I/qtaguid ( 1702): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1702, getuid(): 10012
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6711): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6711): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6711): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1702): No account for auth token provided
,I/qtaguid ( 1702): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1702, getuid(): 10012
,W/Uploader( 1702): No account for auth token provided
,I/qtaguid ( 1702): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1702, getuid(): 10012
,W/Uploader( 1702):  no longer exists, so no auth token.
,I/qtaguid ( 1702): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1702, getuid(): 10012
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 50s ago
,D/SSRM:m  (  907): SIOP:: AP = 310, PST = 337, CUR = 300
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7361): Starting books sync, d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7316152298394257740&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  907): stay LED for fully charged
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
I/qtaguid ( 7361): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
W/ApiaryClient( 7361): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7316152298394257740&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7316152298394257740&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7361): Soft error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7316152298394257740&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7361): Sync error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7316152298394257740&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7361): Finished books sync
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160164, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  907): mCursor = null
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6681): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at dsf.a(PG:807)
E/HttpOperation( 6681): 	at fhk.a(PG:1126)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 8 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 10 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6681): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at ieo.a(PG:43)
E/HttpOperation( 6681): 	at iep.a(PG:93)
E/HttpOperation( 6681): 	at fhn.a(PG:59)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
E/ExperimentLoader( 6681): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): 	at kfv.a(PG:65)
E/ExperimentLoader( 6681): 	at kff.u(PG:385)
E/ExperimentLoader( 6681): 	at kfb.a(PG:29)
E/ExperimentLoader( 6681): 	at kff.l(PG:132)
E/ExperimentLoader( 6681): 	at ieo.a(PG:43)
E/ExperimentLoader( 6681): 	at iep.a(PG:93)
E/ExperimentLoader( 6681): 	at fhn.a(PG:59)
E/ExperimentLoader( 6681): 	at lex.a(PG:85)
E/ExperimentLoader( 6681): 	at lex.b(PG:132)
E/ExperimentLoader( 6681): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6681): 	at fhk.a(PG:908)
E/ExperimentLoader( 6681): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6681): 	at ihi.a(PG:22)
E/ExperimentLoader( 6681): 	at kft.a(PG:91)
E/ExperimentLoader( 6681): 	at kfv.a(PG:62)
E/ExperimentLoader( 6681): 	... 12 more
E/ExperimentLoader( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6681): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6681): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6681): 	at ihi.a(PG:19)
E/ExperimentLoader( 6681): 	... 14 more
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 61235(3MB) AllocSpace objects, 58(3MB) LOS objects, 40% free, 18MB/30MB, paused 924us total 78.078ms
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6681): [getaccountstatus] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at ixd.a(PG:248)
E/HttpOperation( 6681): 	at ixd.b(PG:206)
E/HttpOperation( 6681): 	at ixd.a(PG:175)
E/HttpOperation( 6681): 	at fig.a(PG:78)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/EsSyncAdapterService( 6681): Sync failure
E/EsSyncAdapterService( 6681): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6681): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6681): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6681): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6681): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6681): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6681): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6681): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6681): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6681): 	... 10 more
E/EsSyncAdapterService( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6681): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6681): 	... 12 more
E/EsSyncAdapterService( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6681): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6681): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6681): 	... 14 more
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 191232, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 6
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 310, PST = 330, CUR = 300,
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  907): stay LED for fully charged
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 320, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  907): [PWL] Off : 75s ago
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 315, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/Watchdog(  907): !@Sync 7
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 311, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 308, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 105s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 306, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7361): Starting books sync, d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=538167057694939147&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=538167057694939147&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=538167057694939147&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/BooksSync( 7361): Soft error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=538167057694939147&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7361): Sync error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=538167057694939147&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7361): Finished books sync
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 224350, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  907): Explicit concurrent mark sweep GC freed 44398(2MB) AllocSpace objects, 33(1113KB) LOS objects, 29% free, 37MB/53MB, paused 1.687ms total 135.023ms
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 303, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 140s ago
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 301, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6681): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at dsf.a(PG:807)
E/HttpOperation( 6681): 	at fhk.a(PG:1126)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 8 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 10 more
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6681): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at ieo.a(PG:43)
E/HttpOperation( 6681): 	at iep.a(PG:93)
E/HttpOperation( 6681): 	at fhn.a(PG:59)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/ExperimentLoader( 6681): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): 	at kfv.a(PG:65)
E/ExperimentLoader( 6681): 	at kff.u(PG:385)
E/ExperimentLoader( 6681): 	at kfb.a(PG:29)
E/ExperimentLoader( 6681): 	at kff.l(PG:132)
E/ExperimentLoader( 6681): 	at ieo.a(PG:43)
E/ExperimentLoader( 6681): 	at iep.a(PG:93)
E/ExperimentLoader( 6681): 	at fhn.a(PG:59)
E/ExperimentLoader( 6681): 	at lex.a(PG:85)
E/ExperimentLoader( 6681): 	at lex.b(PG:132)
E/ExperimentLoader( 6681): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6681): 	at fhk.a(PG:908)
E/ExperimentLoader( 6681): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6681): 	at ihi.a(PG:22)
E/ExperimentLoader( 6681): 	at kft.a(PG:91)
E/ExperimentLoader( 6681): 	at kfv.a(PG:62)
E/ExperimentLoader( 6681): 	... 12 more
E/ExperimentLoader( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6681): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6681): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6681): 	at ihi.a(PG:19)
E/ExperimentLoader( 6681): 	... 14 more
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6681): [getaccountstatus] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at ixd.a(PG:248)
E/HttpOperation( 6681): 	at ixd.b(PG:206)
E/HttpOperation( 6681): 	at ixd.a(PG:175)
E/HttpOperation( 6681): 	at fig.a(PG:78)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,E/EsSyncAdapterService( 6681): Sync failure
E/EsSyncAdapterService( 6681): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6681): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6681): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6681): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6681): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6681): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6681): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6681): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6681): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6681): 	... 10 more
E/EsSyncAdapterService( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6681): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6681): 	... 12 more
E/EsSyncAdapterService( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6681): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6681): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6681): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 258152, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 9
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 297, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 296, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/TimaService(  907): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  907): TimaServiceHandler.handleMessage what =1
,D/TimaService(  907): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  907): initializing...
,I/TLC_TIMA_PKM_initialize(  907): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  907): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  907): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  907): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  907): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  907): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  907): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  907): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  907): App is not loaded in QSEE
,D/QSEECOMAPI: (  907): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  907): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  907): Trustlet response is completed
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 180s ago
,D/SSRM:m  (  907): SIOP:: AP = 300, PST = 296, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 7437): Connected to the server!
I/jxcore-log( 7437): 
,I/chromium( 7437): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 8248): MountEmulatedStorage()
,I/ActivityManager(  907): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8248 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8248): v2
I/libpersona( 8248): KNOX_SDCARD checking this for 10081
I/libpersona( 8248): KNOX_SDCARD not a persona
,I/SELinux ( 8248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8248): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8248): TimaSignature is unavailable
,D/ActivityThread( 8248): Added TimaKeyStore provider
,D/ResourcesManager( 8248): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  907): Killing 7009:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,W/libprocessgroup(  907): failed to open /acct/uid_10003/pid_7009/cgroup.procs: No such file or directory
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 294, CUR = 300
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7361): Starting books sync, d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3509780391257004709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3509780391257004709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3509780391257004709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/BooksSync( 7361): Soft error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3509780391257004709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7361): Sync error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=3509780391257004709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7361): Finished books sync
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 316534, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  907): mCursor = null
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  907): !@Sync 11
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6711): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6711): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6711): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6711): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6711): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6711): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6711): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6711): Ignoring header User-Agent because its value was null.
,I/System.out( 6711): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6711): (HTTPLog)-Static: isShipBuild true
I/System.out( 6711): (HTTPLog)-Thread-1093-986174843: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 225s ago
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 291, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 12
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 291, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 291, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 291, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  907): stay LED for fully charged
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 13
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 291, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6681): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at dsf.a(PG:807)
E/HttpOperation( 6681): 	at fhk.a(PG:1126)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 8 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 10 more
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6681): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at ieo.a(PG:43)
E/HttpOperation( 6681): 	at iep.a(PG:93)
E/HttpOperation( 6681): 	at fhn.a(PG:59)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/ExperimentLoader( 6681): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): 	at kfv.a(PG:65)
E/ExperimentLoader( 6681): 	at kff.u(PG:385)
E/ExperimentLoader( 6681): 	at kfb.a(PG:29)
E/ExperimentLoader( 6681): 	at kff.l(PG:132)
E/ExperimentLoader( 6681): 	at ieo.a(PG:43)
E/ExperimentLoader( 6681): 	at iep.a(PG:93)
E/ExperimentLoader( 6681): 	at fhn.a(PG:59)
E/ExperimentLoader( 6681): 	at lex.a(PG:85)
E/ExperimentLoader( 6681): 	at lex.b(PG:132)
E/ExperimentLoader( 6681): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6681): 	at fhk.a(PG:908)
E/ExperimentLoader( 6681): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6681): 	at ihi.a(PG:22)
E/ExperimentLoader( 6681): 	at kft.a(PG:91)
E/ExperimentLoader( 6681): 	at kfv.a(PG:62)
E/ExperimentLoader( 6681): 	... 12 more
E/ExperimentLoader( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6681): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6681): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6681): 	at ihi.a(PG:19)
E/ExperimentLoader( 6681): 	... 14 more
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6681): [getaccountstatus] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at ixd.a(PG:248)
E/HttpOperation( 6681): 	at ixd.b(PG:206)
E/HttpOperation( 6681): 	at ixd.a(PG:175)
E/HttpOperation( 6681): 	at fig.a(PG:78)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/EsSyncAdapterService( 6681): Sync failure
E/EsSyncAdapterService( 6681): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6681): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6681): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6681): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6681): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6681): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6681): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6681): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6681): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6681): 	... 10 more
E/EsSyncAdapterService( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6681): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6681): 	... 12 more
E/EsSyncAdapterService( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6681): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6681): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6681): 	... 14 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 409502, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 2852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  907): Explicit concurrent mark sweep GC freed 48577(2MB) AllocSpace objects, 62(1642KB) LOS objects, 29% free, 37MB/53MB, paused 2.164ms total 114.436ms
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 14
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,E/SMD     (  285): DCD ON
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 15
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 330s ago
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): stay LED for fully charged
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7361): Starting books sync, d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 40135(2MB) AllocSpace objects, 31(2MB) LOS objects, 40% free, 18MB/30MB, paused 681us total 36.788ms
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8210725074622979837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8210725074622979837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8210725074622979837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/BooksSync( 7361): Soft error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8210725074622979837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7361): Sync error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8210725074622979837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7361): Finished books sync
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 471784, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2852): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  907): mCursor = null
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/bootchecker(  315): bootchecker wake up!!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 16
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 17
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 390s ago
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 18
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  907): stay LED for fully charged
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  319): Stop the daemon....
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 19
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 455s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  907): stay LED for fully charged
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  907): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  907): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  907): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ActivityManager(  907): Killing 7024:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,W/libprocessgroup(  907): failed to open /acct/uid_10020/pid_7024/cgroup.procs: No such file or directory
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 21
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 525s ago
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6681): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at dsf.a(PG:807)
E/HttpOperation( 6681): 	at fhk.a(PG:1126)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 8 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 10 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/SMD     (  285): DCD ON
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6681): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at ieo.a(PG:43)
E/HttpOperation( 6681): 	at iep.a(PG:93)
E/HttpOperation( 6681): 	at fhn.a(PG:59)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/ExperimentLoader( 6681): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): 	at kfv.a(PG:65)
E/ExperimentLoader( 6681): 	at kff.u(PG:385)
E/ExperimentLoader( 6681): 	at kfb.a(PG:29)
E/ExperimentLoader( 6681): 	at kff.l(PG:132)
E/ExperimentLoader( 6681): 	at ieo.a(PG:43)
E/ExperimentLoader( 6681): 	at iep.a(PG:93)
E/ExperimentLoader( 6681): 	at fhn.a(PG:59)
E/ExperimentLoader( 6681): 	at lex.a(PG:85)
E/ExperimentLoader( 6681): 	at lex.b(PG:132)
E/ExperimentLoader( 6681): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6681): 	at fhk.a(PG:908)
E/ExperimentLoader( 6681): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6681): 	at ihi.a(PG:22)
E/ExperimentLoader( 6681): 	at kft.a(PG:91)
E/ExperimentLoader( 6681): 	at kfv.a(PG:62)
E/ExperimentLoader( 6681): 	... 12 more
E/ExperimentLoader( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6681): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6681): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6681): 	at ihi.a(PG:19)
E/ExperimentLoader( 6681): 	... 14 more
E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6681): [getaccountstatus] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at ixd.a(PG:248)
E/HttpOperation( 6681): 	at ixd.b(PG:206)
E/HttpOperation( 6681): 	at ixd.a(PG:175)
E/HttpOperation( 6681): 	at fig.a(PG:78)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/EsSyncAdapterService( 6681): Sync failure
E/EsSyncAdapterService( 6681): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6681): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6681): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6681): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6681): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6681): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6681): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6681): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6681): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6681): 	... 10 more
E/EsSyncAdapterService( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6681): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6681): 	... 12 more
E/EsSyncAdapterService( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6681): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6681): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6681): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PanelView( 1172): There is/are notification(s) 
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 670144, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 22
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 23
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7361): Starting books sync, d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9028737932379460899&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 24
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/art     ( 1172): Explicit concurrent mark sweep GC freed 74261(4MB) AllocSpace objects, 51(4MB) LOS objects, 30% free, 37MB/53MB, paused 836us total 76.822ms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9028737932379460899&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9028737932379460899&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7361): Soft error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9028737932379460899&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7361): Sync error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=9028737932379460899&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7361): Finished books sync
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 732236, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  907): Explicit concurrent mark sweep GC freed 57099(4MB) AllocSpace objects, 108(2MB) LOS objects, 29% free, 37MB/53MB, paused 1.896ms total 135.849ms
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
,I/PowerManagerService(  907): [PWL] Off : 600s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON,
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 25
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 26
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 680s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 27
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 28
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 29
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 765s ago
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,D/BatteryService(  907): stay LED for fully charged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/TimaService(  907): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  907): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  907): TimaServiceHandler.handleMessage what =1
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 31
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 32
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  907): [PWL] Off : 855s ago
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 33
,V/AlarmManager(  907): waitForAlarm result :4
,D/LightsService(  907): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  907): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  907): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/GCM     ( 1702): Message class com.google.f.a.a.i
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  907): [SvcLED]  onSensorChanged::light value = 58
,E/LightSensor(  907): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  907): unregisterListener ::   
,D/LightsService(  907): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,E/SMD     (  285): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 34
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 35
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 950s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 36
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 37
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 38
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 39
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 1050s ago
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6681): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at dsf.a(PG:807)
E/HttpOperation( 6681): 	at fhk.a(PG:1126)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 8 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 10 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6681): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at kff.l(PG:132)
E/HttpOperation( 6681): 	at ieo.a(PG:43)
E/HttpOperation( 6681): 	at iep.a(PG:93)
E/HttpOperation( 6681): 	at fhn.a(PG:59)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/ExperimentLoader( 6681): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6681): 	at kfv.a(PG:65)
E/ExperimentLoader( 6681): 	at kff.u(PG:385)
E/ExperimentLoader( 6681): 	at kfb.a(PG:29)
E/ExperimentLoader( 6681): 	at kff.l(PG:132)
E/ExperimentLoader( 6681): 	at ieo.a(PG:43)
E/ExperimentLoader( 6681): 	at iep.a(PG:93)
E/ExperimentLoader( 6681): 	at fhn.a(PG:59)
E/ExperimentLoader( 6681): 	at lex.a(PG:85)
E/ExperimentLoader( 6681): 	at lex.b(PG:132)
E/ExperimentLoader( 6681): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6681): 	at fhk.a(PG:908)
E/ExperimentLoader( 6681): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6681): 	at ihi.a(PG:22)
E/ExperimentLoader( 6681): 	at kft.a(PG:91)
E/ExperimentLoader( 6681): 	at kfv.a(PG:62)
E/ExperimentLoader( 6681): 	... 12 more
E/ExperimentLoader( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6681): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6681): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6681): 	at ihi.a(PG:19)
E/ExperimentLoader( 6681): 	... 14 more
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,E/HttpOperation( 6681): [getaccountstatus] Unexpected exception
E/HttpOperation( 6681): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6681): 	at kfv.a(PG:65)
E/HttpOperation( 6681): 	at kff.u(PG:385)
E/HttpOperation( 6681): 	at kfb.a(PG:29)
E/HttpOperation( 6681): 	at ixd.a(PG:248)
E/HttpOperation( 6681): 	at ixd.b(PG:206)
E/HttpOperation( 6681): 	at ixd.a(PG:175)
E/HttpOperation( 6681): 	at fig.a(PG:78)
E/HttpOperation( 6681): 	at lex.a(PG:85)
E/HttpOperation( 6681): 	at lex.b(PG:132)
E/HttpOperation( 6681): 	at fhk.a(PG:1146)
E/HttpOperation( 6681): 	at fhk.a(PG:908)
E/HttpOperation( 6681): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6681): 	at ihi.a(PG:22)
E/HttpOperation( 6681): 	at kft.a(PG:91)
E/HttpOperation( 6681): 	at kfv.a(PG:62)
E/HttpOperation( 6681): 	... 12 more
E/HttpOperation( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6681): 	at gde.c(Unknown Source)
E/HttpOperation( 6681): 	at gde.b(Unknown Source)
E/HttpOperation( 6681): 	at ihi.a(PG:19)
E/HttpOperation( 6681): 	... 14 more
,E/EsSyncAdapterService( 6681): Sync failure
E/EsSyncAdapterService( 6681): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6681): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6681): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6681): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6681): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6681): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6681): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6681): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6681): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6681): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6681): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6681): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6681): 	... 10 more
E/EsSyncAdapterService( 6681): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6681): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6681): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6681): 	... 12 more
E/EsSyncAdapterService( 6681): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6681): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6681): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6681): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6681): 	... 14 more
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1191358, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  907): mCursor = null
,E/SMD     (  285): DCD ON
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/UsageStatsService(  907): User[0] Flushing usage stats to disk
,D/TimaService(  907): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  907): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  907): TimaServiceHandler.handleMessage what =1
,I/ApplicationUsage(  907): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  907): Updating Usage Statistics in DB @ 1449833413405
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
,W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  907): ::getAppControlDB: Exception to create DB
W/System.err(  907): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  907): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  907): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  907): Done Updating Usage Statistics in DB @ 1449833413664
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 41
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7361): Starting books sync, d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7601189535012563874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
,D/SecContentProvider2(  907): mCursor = null
D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7601189535012563874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 40993(2MB) AllocSpace objects, 30(2MB) LOS objects, 39% free, 18MB/30MB, paused 2.921ms total 101.953ms
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1702): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1702): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  907): uri = 14 selection = getSealedState
D/SecContentProvider2(  907): mCursor = null
,D/SecContentProvider2(  907): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  907): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  907): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1702): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1702): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1702): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1702): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1702): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7361): Authentication error
E/BooksAccountManager( 7361): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7361): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7361): null auth token
I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/qtaguid ( 7361): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7361, getuid(): 10082
,I/qtaguid ( 7361): Untagging socket 34
,W/ApiaryClient( 7361): Error response from books API: {
W/ApiaryClient( 7361):  "error": {
W/ApiaryClient( 7361):   "errors": [
W/ApiaryClient( 7361):    {
W/ApiaryClient( 7361):     "domain": "global",
W/ApiaryClient( 7361):     "reason": "required",
W/ApiaryClient( 7361):     "message": "Login Required",
W/ApiaryClient( 7361):     "locationType": "header",
W/ApiaryClient( 7361):     "location": "Authorization"
W/ApiaryClient( 7361):    }
W/ApiaryClient( 7361):   ],
W/ApiaryClient( 7361):   "code": 401,
W/ApiaryClient( 7361):   "message": "Login Required"
W/ApiaryClient( 7361):  }
W/ApiaryClient( 7361): }
,W/ApiaryClient( 7361): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7601189535012563874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7361): Headers suppressed
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/BooksSync( 7361): Soft error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7601189535012563874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7361): Sync error
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7361): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7601189535012563874&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7361): Headers suppressed
E/BooksSync( 7361): 
E/BooksSync( 7361): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7361): Finished books sync
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  907): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1249046, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  907): mCursor = null
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 42
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  907): [PWL] Off : 1155s ago
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 43
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  907): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 44
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 45
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 285, CUR = 300
,E/Watchdog(  907): !@Sync 46
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 1265s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 283, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 47
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 48
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 277, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 49
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  907): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  907): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  907): TimaServiceHandler.handleMessage what =1
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  907): !@Sync 50
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 273, CUR = 300
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 1380s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 276, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 51
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 277, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 280, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 52
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 53
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 54
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,D/BatteryService(  907): stay LED for fully charged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 1500s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 55
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 56
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 57
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 58
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 1625s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,E/SMD     (  285): DCD ON
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 59
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,D/NetworkStatsFactory(  907): UpdateStatsForKnox
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 270, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  907): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  907): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  907): TimaServiceHandler.handleMessage what =1
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  907): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  907): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryService(  907): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 290, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 61
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,D/BatteryService(  907): stay LED for fully charged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 62
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
,I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryService(  907): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  907): [PWL] Off : 1755s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  907): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  907): !@Sync 63
,V/AlarmManager(  907): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,I/ActivityManager(  907): Killing 7785:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 7730:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 7714:com.android.chrome/u0a88 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 6647:com.sec.chaton/u0a86 (adj 15): empty for 1800s
,D/BatteryService(  907): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  907): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  907): stay LED for fully charged
,I/ActivityManager(  907): Killing 7696:com.sec.knox.bridge/1000 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 7679:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 6860:com.osp.app.signin/u0a45 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 6837:com.policydm/1000 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 7654:com.sec.android.soagent/u0a37 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 7635:com.samsung.klmsagent/u0a19 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 7620:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
,I/ActivityManager(  907): Killing 7596:com.sec.android.diagmonagent/1000 (adj 15): empty for 1801s
,I/ActivityManager(  907): Killing 7578:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1801s
,I/ActivityManager(  907): Killing 5410:com.google.android.music:main/u0a126 (adj 15): empty for 1801s
,I/ActivityManager(  907): Killing 7197:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1801s
,I/ActivityManager(  907): Killing 6819:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,I/ActivityManager(  907): Killing 7851:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1801s
,I/ActivityManager(  907): Killing 4884:com.android.defcontainer/u0a5 (adj 15): empty for 1835s
,I/ActivityManager(  907): Killing 4800:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1837s
,I/ActivityManager(  907): Killing 6074:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1842s
,I/ActivityManager(  907): Killing 7233:com.sec.android.app.music:service/u0a44 (adj 15): empty for 1842s
,I/ActivityManager(  907): Killing 6287:com.google.android.gm/u0a114 (adj 15): empty for 1842s
,I/ActivityManager(  907): Killing 7153:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1843s
,I/ActivityManager(  907): Killing 6752:com.google.android.gms:car/u0a12 (adj 15): empty for 1843s
I/ActivityManager(  907): Killing 7134:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1843s
,I/ActivityManager(  907): Killing 7096:com.samsung.helphub/1000 (adj 15): empty for 1843s
,I/ActivityManager(  907): Killing 7080:com.samsung.android.magazine.service/u0a118 (adj 15): empty for 1843s
I/ActivityManager(  907): Killing 7061:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): empty for 1843s
,I/ActivityManager(  907): Killing 7040:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1843s
,D/LightsService(  907): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  907): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  907): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  907): Prepared write state in 21ms
,D/BatteryService(  907): Sending ACTION_BATTERY_CHANGED.
,I/ProcessStatsService(  907): Prepared write state in 10ms
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3255): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3255): Disconnected process message: 10
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
V/NetworkStats(  907): performPollLocked(flags=0x3)
,D/MotionRecognitionService(  907):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  907): Plugged
I/MotionRecognitionService(  907): setPowerConnected  = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NetworkStatsFactory(  907): UpdateStatsForKnox
,D/ConnectivityService(  907): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
V/NetworkStats(  907): performPollLocked() took 16ms
,D/NtpTrustedTime(  907): currentTimeMillis() cache hit
D/NtpTrustedTime(  907): currentTimeMillis() cache hit
,I/art     (  907): Background sticky concurrent mark sweep GC freed 95584(9MB) AllocSpace objects, 365(6MB) LOS objects, 17% free, 38MB/46MB, paused 7.991ms total 94.220ms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1702): Message class com.google.f.a.a.i
,D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  907): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/EventLogService( 2415): Aggregate from 1449831904338 (log), 1449831904338 (data)
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LightsService(  907): [SvcLED]  onSensorChanged::light value = 36
,E/LightSensor(  907): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  907): unregisterListener ::   
D/LightsService(  907): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-41-18.bin
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_7040/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10112/pid_7061/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10118/pid_7080/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_7096/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10044/pid_7233/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10166/pid_7134/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10114/pid_6287/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10138/pid_7785/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10170/pid_7153/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10128/pid_7730/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10012/pid_6752/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10088/pid_7714/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10048/pid_6074/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_7696/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10086/pid_6647/cgroup.procs: No such file or directory
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,W/libprocessgroup(  907): failed to open /acct/uid_10071/pid_7679/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_6837/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10037/pid_7654/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10011/pid_7620/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10019/pid_7635/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10078/pid_7851/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_7596/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10012/pid_4800/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_6819/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10005/pid_4884/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10004/pid_7197/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10045/pid_6860/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10002/pid_7578/cgroup.procs: No such file or directory
,W/libprocessgroup(  907): failed to open /acct/uid_10126/pid_5410/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8652): 
D/AndroidRuntime( 8652): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8652): CheckJNI is OFF
D/AndroidRuntime( 8652): setted country_code = Germany
D/AndroidRuntime( 8652): setted countryiso_code = DE
D/AndroidRuntime( 8652): setted sales_code = DBT
D/AndroidRuntime( 8652): readGMSProperty: start
D/AndroidRuntime( 8652): readGMSProperty: already setted!!
D/AndroidRuntime( 8652): readGMSProperty: end
D/AndroidRuntime( 8652): addProductProperty: start
E/SMD     (  285): DCD ON
E/AffinityControl( 8652): AffinityControl: registerfunction enter
D/AndroidRuntime( 8652): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  907): START PACKAGE DELETE: observer{633509679}
D/PackageManager(  907): pkg{<packageName>}
D/PackageManager(  907): user{0}
D/PackageManager(  907): caller{2000}
D/PackageManager(  907): flags{3}
D/PersonaManagerService(  907): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  907): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  907): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  907): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  907): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  907): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  907): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  907): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  907): getApplicationUninstallationEnabled
D/ApplicationPolicy(  907): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  907): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  907): Killing 7437:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  907):   Force finishing activity ActivityRecord{8b9733f u0 com.test.thalitest/.MainActivity t12}
D/FocusedStackFrame(  907): Set to : 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1172): value : false
D/SSRM:m  (  907): SIOP:: AP = 290, PST = 276, CUR = 300
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/WifiService(  907): Client connection lost with reason: 4
W/PackageSettings(  907): Skipping PackageSetting{59bc013 com.example.hello/10374} due to missing metadata
D/ConnectivityService(  907): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
D/ResourcesManager(  907): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 4476): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 4.419ms total 50.571ms
W/GeofencerStateMachine( 2216): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8678): MountEmulatedStorage()
E/Zygote  ( 8678): v2
I/libpersona( 8678): KNOX_SDCARD checking this for 10019
I/libpersona( 8678): KNOX_SDCARD not a persona
I/InputReader(  907): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  907): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8678 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/SamsungIME( 1870): mOCRHelper is null
E/libprocessgroup(  907): failed to kill 1 processes for processgroup 7437
I/SELinux ( 8678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1578): Explicit concurrent mark sweep GC freed 34197(2033KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/27MB, paused 528us total 128.852ms
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/TimaKeyStoreProvider( 8678): TimaSignature is unavailable
D/ActivityThread( 8678): Added TimaKeyStore provider
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 8678): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/SurfaceWidgetView( 1490): destroyHardwareResources():741523507
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
V/WindowOrientationListener(  907): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  907): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  907): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  907): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  907): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/Launcher( 1490): onRestart, Launcher: 1071122681
D/Launcher( 1490): onStart, Launcher: 1071122681
D/Launcher.HomeView( 1490): onStart
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2182): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2182): [237392/6] SurfaceWidget drawing first frame
I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/SecContentProvider2(  907): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  907): mCursor = null
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  907): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/RegisteredServicesCache( 1461): empty dynamic service
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/KLMS-2.4.503: ( 8678): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/KLMS-2.4.503: ( 8678): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449834108955
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
I/KLMS-2.4.503: ( 8678): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8678): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/InputMethodManagerService(  907): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 7437 uid 10367
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/EnterpriseDeviceManagerService(  907): Package has changed for user 0
D/EnterpriseDeviceManagerService(  907): Admin package name: com.google.android.gms
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/art     (  907): Explicit concurrent mark sweep GC freed 34179(2MB) AllocSpace objects, 10(273KB) LOS objects, 29% free, 38MB/54MB, paused 9.208ms total 368.340ms
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
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/Timeline(  907): Timeline: Activity_windows_visible id: ActivityRecord{39b29cfc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1907766
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/Zygote  ( 8702): MountEmulatedStorage()
E/Zygote  ( 8702): v2
I/libpersona( 8702): KNOX_SDCARD checking this for 10104
I/libpersona( 8702): KNOX_SDCARD not a persona
D/PackageManager(  907): delete codoeFile: 
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/ActivityManager(  907): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8702 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/PackageManager(  907): result of delete: 1{633509679}
I/ActivityManager(  907): Killing 7808:com.android.email/u0a163 (adj 15): empty for 1803s
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
I/SELinux ( 8702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 8652): Shutting down VM
D/ResourcesManager(  907): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/TimaKeyStoreProvider( 8702): TimaSignature is unavailable
D/ActivityThread( 8702): Added TimaKeyStore provider
D/RCPManagerService(  907): PackageReceiver onReceive()
I/HarmonyEASService(  907): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/libprocessgroup(  907): failed to open /acct/uid_10163/pid_7808/cgroup.procs: No such file or directory
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/KnoxMUMContainerPolicy(  907): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/BackupManagerService(  907): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  907): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  907): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  907): uID is 10367
V/EnterpriseBillingPolicy(  907): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  907): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  907): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  907): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  907): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  907): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  907): getBillingProfileForVpnEngine - end - null
D/ResourcesManager( 8702): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/TaskPersister(  907): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  907): removeObsoleteFile: deleting file=12_task_thumbnail.png
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/elm:14451( 8702): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14451( 8702): ELMEngine.ELMEngine( context ).
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14451( 8702): MDMBridge.setEnterpriseBridge()
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/elm:14451( 8702): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14451( 8702): ElmAgentService : onCreate()
D/elm:14451( 8702): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8702): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8702): MDMBridge.getInstance()
D/elm:14451( 8702): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/elm:14451( 8702): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/Zygote  ( 8718): MountEmulatedStorage()
E/Zygote  ( 8718): v2
I/libpersona( 8718): KNOX_SDCARD checking this for 10017
I/libpersona( 8718): KNOX_SDCARD not a persona
I/ActivityManager(  907): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8718 uid=10017 gids={50017, 9997} abi=armeabi-v7a
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
I/SELinux ( 8718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/elm:14451( 8702): ElmAgentService : onDestroy().
I/ActivityManager(  907): Killing 7509:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1803s
I/SELinux ( 8718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8718): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  907): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  907): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  907): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 8718): TimaSignature is unavailable
D/ActivityThread( 8718): Added TimaKeyStore provider
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager( 8718): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
W/libprocessgroup(  907): failed to open /acct/uid_1000/pid_7509/cgroup.procs: No such file or directory
D/ResourcesManager(  907): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  907): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8718): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8718): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8718): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  907): checkUser: useridlist=null, currentuser=0
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
E/Zygote  ( 8734): MountEmulatedStorage()
E/Zygote  ( 8734): v2
I/libpersona( 8734): KNOX_SDCARD checking this for 1000
I/libpersona( 8734): KNOX_SDCARD not a persona
I/ActivityManager(  907): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8734 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  907): Killing 7886:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1803s
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  907): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  907): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  907): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  907): onPackageRemoved : com.test.thalitest
I/SELinux ( 8734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8734): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  907): failed to open /acct/uid_10178/pid_7886/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 8734): TimaSignature is unavailable
D/ActivityThread( 8734): Added TimaKeyStore provider
D/ResourcesManager( 8734): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8734): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8734): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8734): new DMDBOpenHelper instance
E/SQLiteDatabase( 8734): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase( 8734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 8734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8734): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase( 8734): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8734): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8734): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 8734): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 8734): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 8734): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8734): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 8734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8734): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8734): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 8734): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8734): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8734): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 8734): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 8734): Shutting down VM
E/AndroidRuntime( 8734): FATAL EXCEPTION: main
E/AndroidRuntime( 8734): Process: com.sec.pcw.device, PID: 8734
E/AndroidRuntime( 8734): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8734): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5456)
E/AndroidRuntime( 8734): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/AndroidRuntime( 8734): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/AndroidRuntime( 8734): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8734): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/AndroidRuntime( 8734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8734): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8734): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/AndroidRuntime( 8734): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8734): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8734): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 8734): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 8734): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 8734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8734): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime( 8734): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8734): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8734): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/AndroidRuntime( 8734): 	... 11 more
I/EventHub(  907): Removing device '/dev/input/event4' due to inotify event
I/EventHub(  907): Removing device '/dev/input/event5' due to inotify event
I/EventHub(  907): Removing device '/dev/input/event6' due to inotify event
I/EventHub(  907): Removing device '/dev/input/event7' due to inotify event
I/EventHub(  907): Removing device '/dev/input/event8' due to inotify event
I/EventHub(  907): Removing device '/dev/input/event9' due to inotify event
I/EventHub(  907): Removing device '/dev/input/event10' due to inotify event
I/EventHub(  907): Removing device '/dev/input/event11' due to inotify event
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
