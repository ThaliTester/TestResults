#### Test 5497026179923a9_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7268): null auth token
I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
I/qtaguid ( 7268): Untagging socket 34
W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
W/ApiaryClient( 7268): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7046921731032202788&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
--------- beginning of system
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AndroidRuntime( 7311): 
D/AndroidRuntime( 7311): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7311): CheckJNI is OFF
D/AndroidRuntime( 7311): setted country_code = Germany
D/AndroidRuntime( 7311): setted countryiso_code = DE
D/AndroidRuntime( 7311): setted sales_code = DBT
D/AndroidRuntime( 7311): readGMSProperty: start
D/AndroidRuntime( 7311): readGMSProperty: already setted!!
D/AndroidRuntime( 7311): readGMSProperty: end
D/AndroidRuntime( 7311): addProductProperty: start
E/AffinityControl( 7311): AffinityControl: registerfunction enter
D/AndroidRuntime( 7311): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  891): inState():  stateMachine is null !!
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  891): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SQLiteSecureOpenHelper( 3591): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3591): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/AndroidRuntime( 7311): Shutting down VM
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 51
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  891): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 891) 
D/LightsService(  891): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  891): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1172): Icon Only
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/WindowManager(  891): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1172): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
E/Zygote  ( 7332): MountEmulatedStorage()
E/Zygote  ( 7332): v2
I/libpersona( 7332): KNOX_SDCARD checking this for 10367
I/libpersona( 7332): KNOX_SDCARD not a persona
D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7332 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7332): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1172): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@7d645a9
D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/TimaKeyStoreProvider( 7332): TimaSignature is unavailable
D/ActivityThread( 7332): Added TimaKeyStore provider
V/ActivityManager(  891): Display changed displayId=0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7332): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
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
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/BooksSync( 7268): Soft error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7046921731032202788&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7268): Sync error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7046921731032202788&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7268): Finished books sync
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64157, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  891): Killing 5958:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/libprocessgroup(  891): failed to open /acct/uid_10004/pid_5958/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/WebViewFactory( 7332): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7332): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/LibraryLoader( 7332): Loading: webviewchromium
I/LibraryLoader( 7332): Time to load native libraries: 2 ms (timestamps 6266-6268)
I/LibraryLoader( 7332): Expected native library version number "",actual native library version number ""
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
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
V/WebViewChromiumFactoryProvider( 7332): Binding Chromium to main looper Looper (main, tid 1) {3042d042}
I/LibraryLoader( 7332): Expected native library version number "",actual native library version number ""
I/chromium( 7332): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7332): Initializing chromium process, renderers=0
W/art     ( 7332): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7332): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7332): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7332): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7332): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7332): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7332): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7332): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7332): Remote Branch: 
I/Adreno-EGL( 7332): Local Patches: 
I/Adreno-EGL( 7332): Reconstruct Branch: 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/chromium( 7332): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7332): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/art     ( 7332): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7332): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/SystemWebViewEngine( 7332): CordovaWebView is running on device made by: samsung
D/PowerManagerService(  891): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1172 (0x0)
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/art     ( 7332): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7332): Attempt to remove local handle scope entry from IRT, ignoring
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
D/Activity( 7332): performCreate Call secproduct feature valuefalse
D/Activity( 7332): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/OpenGLRenderer( 7332): Render dirty regions requested: true
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ActivityManager(  891): post active user change for 0
D/KnoxTimeoutHandler(  891): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  891): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
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
I/OpenGLRenderer( 7332): Initialized EGL, version 1.4
I/OpenGLRenderer( 7332): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7332): Enabling debug mode 0
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/ActivityManager(  891): Displayed com.test.thalitest/.MainActivity: +780ms
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
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  891): mDVFSHelper.release()
I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{2f6b1e3f u0 com.test.thalitest/.MainActivity t12} time:96797
D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@10
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
I/art     (  891): Explicit concurrent mark sweep GC freed 42097(2MB) AllocSpace objects, 12(1667KB) LOS objects, 29% free, 37MB/53MB, paused 1.455ms total 131.607ms
,D/JsMessageQueue( 7332): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline( 7332): Timeline: Activity_idle id: android.os.BinderProxy@2c570cfd time:96879
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/GAV2    ( 7268): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (6/8)
,I/SurfaceFlinger(  249): id=15 Removed Starting com.test.thalitest (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/jxcore_app_log( 7332): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1360644096
,D/JX-Cordova( 7332): jxcore cordova android initializing
,V/AlarmManager(  891): waitForAlarm result :4
,D/SSRM:m  (  891): SIOP:: AP = 350, PST = 418, CUR = 300
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6668): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  279): DCD ON
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,W/jxcore-log( 7332): Initializing JXcore engine
,W/jxcore-log( 7332): JXcore engine is ready
,W/jxcore-log( 7332): Starting JXcore engine
,E/auditd  ( 2047): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  891): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  891): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7394): MountEmulatedStorage()
E/Zygote  ( 7394): v2
I/libpersona( 7394): KNOX_SDCARD checking this for 1000
I/libpersona( 7394): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7394): TimaSignature is unavailable
,D/ActivityThread( 7394): Added TimaKeyStore provider
,D/ResourcesManager( 7394): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7394):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7394):  SeDenialReceiver : File path = null
,I/ActivityManager(  891): Killing 5997:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,W/jxcore-log( 7332): Platform android
W/jxcore-log( 7332): 
,W/jxcore-log( 7332): Process ARCH arm
W/jxcore-log( 7332): 
,W/libprocessgroup(  891): failed to open /acct/uid_10044/pid_5997/cgroup.procs: No such file or directory
,I/jxcore-log( 7332): JXcore Cordova bridge is ready!
I/jxcore-log( 7332): 
,W/jxcore-log( 7332): JXcore engine is started
,E/Adreno-ES20( 7332): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7332): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/jxcore-log( 7332): Toggling radios to true
I/jxcore-log( 7332): 
,D/BluetoothAdapter( 7332): enable()
,D/BluetoothAdapter( 7332): enable(): BT is already enabled..!
,D/WifiService(  891): New client listening to asynchronous messages
,I/WifiManager( 7332): packageName : com.test.thalitest
,D/SecContentProvider(  891): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  891): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  891): mCursor = null
,D/WifiService(  891): setWifiEnabled: true pid=7332, uid=10367
E/WifiService(  891): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  891): Permission Denial: getCurrentUser() from pid=7332, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  891): Failed getting userId using ActivityManagerNative
W/WifiService(  891): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7332, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  891): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  891): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  891): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  891): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  891): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  891): name = wifi_on
,I/WifiService(  891): disconnect: pid=7332, uid=10367
,I/wpa_supplicant( 1262): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7332): Radios toggled
I/jxcore-log( 7332): 
,I/jxcore-log( 7332): My device name is: samsung-SM-G900F
I/jxcore-log( 7332): 
,I/wpa_supplicant( 1262): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1262): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1262): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1262): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  891): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1262): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1262): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1262): Disconnected - do not scan
I/wpa_supplicant( 1262): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  891): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  891): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  891): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TaskPersister(  891): removeObsoleteFile: deleting file=11_task_thumbnail.png
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  891): InactiveState{ what=143375 }
,D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  272): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1704): Read error: ssl=0xaf13be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1704): SSL shutdown failed: ssl=0xaf13be00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  891): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): ignoring duplicate network state non-change
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,E/WifiStateMachine(  891): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-4ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Validated
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/wpa_supplicant( 1262): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1262): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1262): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1262): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1262): First Scan Start
,E/WifiStateMachine(  891): ConnectModeState: Network connection lost 
,I/wpa_supplicant( 1262): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  891): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  891): InactiveState{ what=143375 }
D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1307): Starting #6
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  891): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/EntConnectivity(  891): Not allowed due to - mEnabled false
D/ConnectivityService(  891): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  891): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  272): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
,E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  891): updateConfiguredNetworkExpiration - currTime: 1452509416962
D/ConnectivityService(  891): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiStateMachine(  891): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/ConnectivityService(  891): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,D/CSLegacyTypeTracker(  891): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,E/WifiStateMachine(  891): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/CSLegacyTypeTracker(  891): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1461): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  891): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  891): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  891): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  891): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,V/NetworkStats(  891): updateIfacesLocked()
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): performPollLocked(flags=0x1)
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,E/ConnectivityService(  891): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,V/NetworkStats(  891): performPollLocked() took 5ms
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  891): setDetailed state send new extra info"NG700"
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,I/Hs20UtilService( 1307): Starting #7
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Set preference state off
D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,V/NearbySettings( 1307): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  891): updateDataUsageMap
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2200): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  891): MasterInitialState.processMessage what=3
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  891): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  891): CLoinfo wifi false
,W/SLocation(  891): No Active Data Connection
,I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/PCWCLIENTTRACE_PushUtil( 6774): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6774): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6774): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6774): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5400): type=WIFI subType= reason=null isConnected=false
I/PCWCLIENTTRACE_SYSTEMReceiver( 6774): noConnectivity : true
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7461): MountEmulatedStorage()
E/Zygote  ( 7461): v2
I/libpersona( 7461): KNOX_SDCARD checking this for 10002
I/libpersona( 7461): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7461 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7461): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7461): TimaSignature is unavailable
,D/ActivityThread( 7461): Added TimaKeyStore provider
,D/ResourcesManager( 7461): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  891): Killing 6274:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7478): MountEmulatedStorage()
E/Zygote  ( 7478): v2
I/libpersona( 7478): KNOX_SDCARD checking this for 1000
I/libpersona( 7478): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7478 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7478): TimaSignature is unavailable
,D/ActivityThread( 7478): Added TimaKeyStore provider
,D/PowerManagerService(  891): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  891): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  891): [s] DisplayPowerCallbacks : onStateChanged()
,D/ResourcesManager( 7478): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  891): failed to open /acct/uid_10117/pid_6274/cgroup.procs: No such file or directory
,D/lights  (  891): lcd : 34 +
,D/lights  (  891): lcd : 34 -
,D/lights  (  891): lcd : 25 +
,D/lights  (  891): lcd : 25 -
,I/DIAGMON_AGENT( 7478): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7478): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/lights  (  891): lcd : 17 +
,D/lights  (  891): lcd : 17 -
,D/DisplayPowerController(  891): getFinalBrightness : 15 -> 15
D/lights  (  891): lcd : 15 +
,D/lights  (  891): lcd : 15 -
,D/DisplayPowerController(  891): getFinalBrightness : 15 -> 15
,E/SMD     (  279): DCD ON
,I/DIAGMON_AGENT( 7478): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7478): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7478): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7478): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7494): MountEmulatedStorage()
,E/Zygote  ( 7494): v2
I/libpersona( 7494): KNOX_SDCARD checking this for 10011
I/libpersona( 7494): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7494 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 271us total 11.072ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 8.991ms
,I/wpa_supplicant( 1262): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1262): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1262): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1262): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1262): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  891): [1,452,509,418,011 ms] noteScanEnd no scan source
,E/WifiStateMachine(  891): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@8307052 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info0x
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 15.497ms
,I/SELinux ( 7494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/CLocInfoService(  891): External Intent Received android.net.wifi.SCAN_RESULTS
I/SELinux ( 7494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7494): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7494): TimaSignature is unavailable
,D/ActivityThread( 7494): Added TimaKeyStore provider
,D/ResourcesManager( 7494): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1262): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1262): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/wpa_supplicant( 1262): Associated with C0.AA.48
,I/ActivityManager(  891): Killing 6566:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/FOTA_Client( 7494): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7494): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1262): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1262): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  891): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  891): mCursor = null
,I/wpa_supplicant( 1262): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1262): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1262): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 1262): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1262): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1262): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1262): Blacklist: Clear (temp) 
I/wpa_supplicant( 1262): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  891): Network connection established
,D/WifiNative-HAL(  891): callSECApiVoid - ID [50]
,E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  891): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  891): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  891): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  891): Got NetworkAgent Messenger
D/ConnectivityService(  891): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891): NetworkAgent connected
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/FOTA_Client( 7494): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7494): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7494): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  891): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  891): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  272): Setting iface cfg
,E/WifiStateMachine(  891): Start Dhcp Watchdog 2
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  891): mCursor = null
,W/libprocessgroup(  891): failed to open /acct/uid_10075/pid_6566/cgroup.procs: No such file or directory
,E/Zygote  ( 7510): MountEmulatedStorage()
E/Zygote  ( 7510): v2
I/libpersona( 7510): KNOX_SDCARD checking this for 10019
I/libpersona( 7510): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7510 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6583:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,E/WifiStateMachine(  891): calculateWifiScore() report new score 60
,I/WifiStateMachine(  891): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  891): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/ConnectivityService(  891): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/SELinux ( 7510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7510): TimaSignature is unavailable
,D/ActivityThread( 7510): Added TimaKeyStore provider
,D/ResourcesManager( 7510): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_6583/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7510): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7510): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452509418245
,I/KLMS-2.4.503: ( 7510): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7510): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.503: ( 7510): StateImplV2(): networkChangeListener().END
I/ActivityManager(  891): Killing 6623:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  891): do suspend false
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2(  891): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService(  891): InactiveState{ what=143375 }
,D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  891): mCursor = null
,E/Zygote  ( 7525): MountEmulatedStorage()
,E/Zygote  ( 7525): v2
I/libpersona( 7525): KNOX_SDCARD checking this for 10037
I/libpersona( 7525): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7525 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7525): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7525): TimaSignature is unavailable
,D/ActivityThread( 7525): Added TimaKeyStore provider
,D/ResourcesManager( 7525): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7525): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_6623/cgroup.procs: No such file or directory
,E/SPPClientService( 5335): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6816): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6816): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6816): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 6816): [SLFUCHKMGR] constructor called
,I/SA      ( 6816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6816): [OR] == isSIMCardReady false ==
,I/SA      ( 6816): [SCU] == networkStateCheck == false
I/SA      ( 6816): [OR] onReceive END
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 5335): [[SystemStateMonitorService]] No Active Internet
,E/Zygote  ( 7542): MountEmulatedStorage()
I/libpersona( 7542): KNOX_SDCARD checking this for 10071
E/Zygote  ( 7542): v2
I/libpersona( 7542): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7542 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  891): Killing 6737:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
I/SELinux ( 7542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7542): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7542): TimaSignature is unavailable
,D/ActivityThread( 7542): Added TimaKeyStore provider
,E/dhcpcd  ( 7555): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7555): version 5.5.6 starting
,E/dhcpcd  ( 7555): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ResourcesManager( 7542): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7542): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7542): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7542): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/libprocessgroup(  891): failed to open /acct/uid_10015/pid_6737/cgroup.procs: No such file or directory
,I/dhcpcd  ( 7555): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7555): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7555): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7555): bssid match
,I/dhcpcd  ( 7555): wlan0: rebinding lease of 192.168.1.135
,D/comsamsunglog( 7542): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7542): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7542): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
,D/comsamsunglog( 7542): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7542): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7542): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7542): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7542): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  891): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  891): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  891): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  891): selectionArgs: false
D/SettingsProvider(  891): selectionArgs: 10071
D/SecContentProvider(  891): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  891): ret = -1
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7542): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7542): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7542): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7542): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7542): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7542): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7542): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7542): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1334): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7542): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7542): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7570): MountEmulatedStorage()
E/Zygote  ( 7570): v2
I/libpersona( 7570): KNOX_SDCARD checking this for 1000
I/libpersona( 7570): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7570 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6758:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SELinux ( 7570): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7570): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7570): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7570): TimaSignature is unavailable
,D/ActivityThread( 7570): Added TimaKeyStore provider
,D/ResourcesManager( 7570): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7570): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_6758/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 7570): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7570): premStatus:2
,I/KnoxUsageLogPro( 7570): isEulaShown : false
,I/KnoxUsageLogPro( 7570): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7585): MountEmulatedStorage()
E/Zygote  ( 7585): v2
I/libpersona( 7585): KNOX_SDCARD checking this for 10088
I/libpersona( 7585): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7585 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6537:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,I/SELinux ( 7585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7585): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7585): TimaSignature is unavailable
,D/ActivityThread( 7585): Added TimaKeyStore provider
,D/ResourcesManager( 7585): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  891): failed to open /acct/uid_10034/pid_6537/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 4814:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,D/Headlines( 5532): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5532): getCountryCode(): countryCode = DE
,D/Headlines( 5532): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,E/Zygote  ( 7604): MountEmulatedStorage()
I/libpersona( 7604): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7604): v2
I/libpersona( 7604): KNOX_SDCARD not a persona
,D/Headlines( 5532): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7604 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/HeadlinesCardManager( 5532): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5532): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7604): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7604): TimaSignature is unavailable
,D/ActivityThread( 7604): Added TimaKeyStore provider
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_4814/cgroup.procs: No such file or directory
,D/ResourcesManager( 7604): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/dhcpcd  ( 7555): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/dhcpcd  ( 7555): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/WifiP2pService(  891): InactiveState{ what=143375 }
,E/WifiStateMachine(  891): WifiStateMachine DHCP successful
D/WifiP2pService(  891): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  891): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  891): Not connected state, yet.
E/WifiStateMachine(  891): VerifyingLinkState enter
,D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,D/WifiStateMachine(  891): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  891): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  891): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  891): callSECApiInt - ID [210]
,E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  891): updateNetworkInfo()
,D/ConnectivityService(  891): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  891): Adding iface wlan0 to network 503
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ConnectivityService(  891): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  891): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  891): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  891): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  891): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  891): updateSourceRoutes : add src route for:192.168.1.135
,V/        (  272): QcRouteController
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7604): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,V/        (  272): QcRouteController
,V/        (  272): QcRouteController
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  891): updateDnsLinkProperty: enter
V/        (  272): QcRouteController
,D/WifiWatchdogStateMachine.DnsPinger(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  891): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  891): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  891): Now, connected state.
E/WifiStateMachine(  891): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  891): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/        (  272): QcRouteController
,E/WifiStateMachine(  891): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  891): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  891): mBoosterFLAG : 0
I/WifiTrafficPoller(  891): current booster mode : FullMode
,E/WifiStateMachine(  891): ConnectedState Enter  mScreenOn=true scanperiod=20000
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNative-HAL(  891): callSECApiVoid - ID [212]
,V/        (  272): QcRouteController
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,V/        (  272): QcRouteController
,I/CLocInfoService(  891): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  891): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,V/        (  272): QcRouteController
,D/ConnectivityService(  891): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  891): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891): ignoring duplicate network state non-change
E/ConnectivityService(  891): updateNetworkInfo()
D/ConnectivityService(  891): ignoring duplicate network state non-change
E/ConnectivityService(  891): updateNetworkInfo()
,D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Validated
,D/ConnectivityService(  891):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  891): currentScore = 0, newScore = 60
D/ConnectivityService(  891):    accepting network in place of null
D/ConnectivityService(  891): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1461): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  891): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  891): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  891): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/ConnectivityService(  891): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  891): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,V/NetworkStats(  891): updateIfacesLocked()
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): performPollLocked(flags=0x1)
D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): performPollLocked() took 3ms
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
,D/ConnectivityService(  891): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  891):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  891): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/NtpTrustedTime(  891): currentTimeMillis() cache hit
V/NetworkStats(  891): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
D/NtpTrustedTime(  891): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/WebViewFactory( 7604): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7604): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7604): Loading: webviewchromium
I/LibraryLoader( 7604): Time to load native libraries: 4 ms (timestamps 2097-2101)
I/LibraryLoader( 7604): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7604): Binding Chromium to main looper Looper (main, tid 1) {147cf250}
I/LibraryLoader( 7604): Expected native library version number "",actual native library version number ""
I/chromium( 7604): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7604): Initializing chromium process, renderers=0
W/art     ( 7604): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7604): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7604): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 7604): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7604): Requires BLUETOOTH permission
,I/Adreno-EGL( 7604): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7604): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7604): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7604): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7604): Remote Branch: 
I/Adreno-EGL( 7604): Local Patches: 
I/Adreno-EGL( 7604): Reconstruct Branch: 
,I/NSApplication( 7604): Starting up...
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7702): MountEmulatedStorage()
E/Zygote  ( 7702): v2
I/libpersona( 7702): KNOX_SDCARD checking this for 10138
I/libpersona( 7702): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7702 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6058:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7702): TimaSignature is unavailable
,D/ActivityThread( 7702): Added TimaKeyStore provider
,D/ResourcesManager( 7702): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7702): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7702): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7702): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup(  891): failed to open /acct/uid_10042/pid_6058/cgroup.procs: No such file or directory
,D/QuickConnect( 7702): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7702): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7702): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7717): MountEmulatedStorage()
E/Zygote  ( 7717): v2
I/libpersona( 7717): KNOX_SDCARD checking this for 10163
I/libpersona( 7717): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7717 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6018:com.sec.android.gallery3d/u0a48 (adj 15): bgCount ##41
,I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
,D/ActivityThread( 7717): Added TimaKeyStore provider
,D/ResourcesManager( 7717): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7717): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7717): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7717): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7717): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  891): failed to open /acct/uid_10048/pid_6018/cgroup.procs: No such file or directory
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,E/Zygote  ( 7743): MountEmulatedStorage()
I/libpersona( 7743): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7743): v2
I/libpersona( 7743): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7743 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  891): MasterInitialState.processMessage what=3
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  891): SmartBondingReceiver: wifi is connected
,D/SmartBondingService(  891): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,I/CLocInfoService(  891): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  891): CLocinfo wifi true 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 7743): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/accuweather( 2200): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2101): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2101): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,I/DBG_DM  ( 3810): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5400): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7743): TimaSignature is unavailable
,D/ActivityThread( 7743): Added TimaKeyStore provider
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
I/ActivityManager(  891): Killing 5683:com.android.mms/u0a50 (adj 15): bgCount ##41
V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7743): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/SecurityLogAgent( 7394): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7394): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7394): StateMachine : Current State = 1
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7394): StateMachine : Changed Current State = 1
,I/ActivityManager(  891): Killing 6840:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,D/CountryDetector(  891): No listener is left
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): last run: 1452509335763 -- System.currentTimeMillis()-last_run: 84334
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip last_72_check
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7743): onCreate
,D/BadgeProvider( 7743): DatabaseHelper
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,E/Zygote  ( 7767): MountEmulatedStorage()
E/Zygote  ( 7767): v2
I/libpersona( 7767): KNOX_SDCARD checking this for 10178
I/libpersona( 7767): KNOX_SDCARD not a persona
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,I/ActivityManager(  891): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7767 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/SELinux ( 7767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7767): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7743): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
D/TimaKeyStoreProvider( 7767): TimaSignature is unavailable
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
D/ActivityThread( 7767): Added TimaKeyStore provider
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,D/BadgeProvider( 7743): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7743): sendNotify, [notify] : null
D/BadgeProvider( 7743): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7743): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7743): update, [UpdateCount] : 1
,D/Launcher.Model( 1488): reloadBadges entered.
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/ResourcesManager( 7767): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7717): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,I/ActivityManager(  891): Killing 6856:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  891): failed to open /acct/uid_10050/pid_5683/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10051/pid_6840/cgroup.procs: No such file or directory
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2486): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2486): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7133): notifyNetworkActivated
,W/libprocessgroup(  891): failed to open /acct/uid_10058/pid_6856/cgroup.procs: No such file or directory
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 7133): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  891): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2486): [AccountUtils] Account not ready
W/Kids    ( 2486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2486): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2486): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2486): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2486): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2486): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2486): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2486): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,W/ActivityManager(  891): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/PanelView( 1172): There is/are notification(s) 
,D/hcjo    ( 7133): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7133): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7133): exit::IDLE
D/InitializeManagerStateMachine( 7133): entry::NETWORK_CHECK
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7133): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7133): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7133): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7133): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7133): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7133): entry::SUCCESS
D/hcjo    ( 7133): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1307): Starting #8
,D/hcjo    ( 7133): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7133): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 1307): Message received 5007
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/InitializeManagerStateMachine( 7133): exit::SUCCESS
V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/InitializeManagerStateMachine( 7133): entry::IDLE
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1307): Starting #9
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  891): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/Hs20UtilService( 1307): Starting #10
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1307): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1307): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1307): Starting #11
,I/Hs20UtilService( 1307): Message received 5007
,D/NearbySettings( 1307): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1307): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  891): callSECApi what=220
D/WifiStateMachine(  891): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 6774): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6774): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6774): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6774): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/DIAGMON_AGENT( 7478): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7478): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService(  891): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891
,D/DisplayPowerController(  891): getFinalBrightness : 42 -> 42
,D/PowerManagerService(  891): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  891): lcd : 22 +
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  891): lcd : 22 -
,D/lights  (  891): lcd : 30 +
,D/lights  (  891): lcd : 30 -
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/lights  (  891): lcd : 39 +
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7494): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7494): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
D/lights  (  891): lcd : 39 -
,I/FOTA_Client( 7494): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/DisplayPowerController(  891): getFinalBrightness : 42 -> 42
I/FOTA_Client( 7494): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,D/lights  (  891): lcd : 42 +
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/FOTA_Client( 7494): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7510): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7510): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452509420587
,I/KLMS-2.4.503: ( 7510): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7510): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7510): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7510): NetworkChangeOperations(): uploadRequestLog().START 
,D/lights  (  891): lcd : 42 -
,D/DisplayPowerController(  891): getFinalBrightness : 42 -> 42
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/KLMS-2.4.503: ( 7510): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SO_AGENT( 7525): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5335): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6816): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6816): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6816): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
I/SA      ( 6816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6816): [OR] == isSIMCardReady false ==
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6816): [SCU] == networkStateCheck == true
,I/SA      ( 6816): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6816): isChinaCountryCode : false
I/SA      ( 6816): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6816): [OR] == networkStateCheck true ==
,I/SA      ( 6816): [OR] GetMyCountryZoneTask
,I/SA      ( 6816): [OR] onReceive END
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SA      ( 6816): [SRS] prepareGetMyCountryZone
,D/accuweather( 7542): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7542): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6816): [SSP] query invoked
,I/KnoxUsageLogPro( 7570): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7570): premStatus:2
I/KnoxUsageLogPro( 7570): isEulaShown : false
I/KnoxUsageLogPro( 7570): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
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
,I/art     (  891): Explicit concurrent mark sweep GC freed 68038(3MB) AllocSpace objects, 6(161KB) LOS objects, 29% free, 37MB/53MB, paused 1.338ms total 88.080ms
,I/SA      ( 6816): [TPMU] GetMccFromDB : null
I/SA      ( 6816): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6816): [TPM] isNoProxy(default) : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/Headlines( 5532): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5532): getCountryCode(): countryCode = DE
,D/Headlines( 5532): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5532): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5532): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5532): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5532): requestUpdateNewsWelcomeCard !!! no welcome card
,E/File    ( 6816): fail readDirectory() errno=2
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7702): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/QuickConnect( 7702): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7702): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  891): exchangeData() failure , invalid userId
D/RCPManagerService(  891): exchangeData() failure , invalid userId
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7394): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7394): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7394): StateMachine : Current State = 1
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7394): StateMachine : Changed Current State = 1
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SMD     (  279): DCD ON
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): 
D/com.peel.receiver.ConnectivityActionReceiver( 1823): last run: 1452509335763 -- System.currentTimeMillis()-last_run: 85105
D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip 
,D/com.peel.receiver.ConnectivityActionReceiver( 1823): ... skip last_72_check
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ChimeraCfgMgr( 2486): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2486): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/hcjo    ( 7133): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7133): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7133): exit::IDLE
D/InitializeManagerStateMachine( 7133): entry::NETWORK_CHECK
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7133): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7133): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7133): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7133): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7133): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7133): entry::SUCCESS
D/hcjo    ( 7133): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7133): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7133): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  891): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  891): identical MTU - not setting
D/ConnectivityService(  891): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  891): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,D/SmartBondingService(  891): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
V/        (  272): QcRouteController
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  891): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
D/SmartBondingService(  891): getSBEnabled() enabled =false
,D/InitializeManagerStateMachine( 7133): exit::SUCCESS
D/InitializeManagerStateMachine( 7133): entry::IDLE
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/        (  272): QcRouteController
,W/NetworkManagementService(  891): route cmd failed: 
W/NetworkManagementService(  891): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  891): '
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  891): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  891): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  891): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  891): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  891): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ConnectivityService(  891): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  891): calling update connectivity
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  891):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
D/ConnectivityService(  891): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2486): [AccountUtils] Account not ready
W/Kids    ( 2486): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2486): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2486): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2486): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2486): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2486): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2486): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2486): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2486): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/Watchdog(  891): !@Sync 3
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SA      ( 6816): [RC New] Execute method=[GET] start
,I/SA      ( 6816): [RC New] Security=[true]
,I/System.out( 6816): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6816): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6816): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 6816): [RC New] [v2liruge] api execute + 710
I/SA      ( 6816): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6816): AsyncTask #1 calls detatch()
,I/SA      ( 6816): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6816): [OCP] update openData : PL
,I/SA      ( 6816): [TPMU] getNetworkMcc : 
,I/SA      ( 6816): [SCU] saveMccToPreferece Start
,I/SA      ( 6816): [SCU] RegionMCC : 260
I/SA      ( 6816): [SSP] query invoked
,I/SA      ( 6816): [TPMU] GetMccFromDB : null
,I/SA      ( 6816): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6816): [SCU] saveMccToPreferece End
,I/SA      ( 6816): [RC New] executeRequest [v2liruge] end. 767
,I/SA      ( 6816): [RC New] Execute end
,I/SA      ( 6816): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6816): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  891): REQUEST_POWER_SAVE_ON
I/dhcpcd  ( 7555): wlan0: sending IPv6 Router Solicitation
,E/WifiStateMachine(  891): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PowerManagerService(  891): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  891): [PWL] On : 76371 (30000 ms ago)
I/PowerManagerService(  891): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  891): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=891, ws=WorkSource{10059}) (elapsedTime=3259)
,E/SMD     (  279): DCD ON
,I/jxcore-log( 7332): Test app app.js loaded
I/jxcore-log( 7332): 
,I/Choreographer( 7332): Skipped 431 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7332): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7332): 
,I/chromium( 7332): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7332): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PowerManagerService(  891): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 891) eventTime = 106589
,D/PowerManagerService(  891): [s] UserActivityState : 4 -> 1
D/PowerManagerService(  891): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=891 (0x0)
D/PowerManagerService(  891): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=891, ws=WorkSource{10059}) (elapsedTime=3479)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
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
D/LockPatternUtilsCache( 1172): value : false
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/GAV4    ( 7604): Thread[GAThread,5,main]: No campaign data found.
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
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SSRM:m  (  891): SIOP:: AP = 400, PST = 416, CUR = 300
,I/SurfaceFlinger(  249): id=17 Removed Toast (8/8)
I/SurfaceFlinger(  249): id=17 Removed Toast (-2/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ProcessCpuTracker(  891): Skipping unknown process pid 7816
,W/ProcessCpuTracker(  891): Skipping unknown process pid 7817
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ProcessCpuTracker(  891): Skipping unknown process pid 7819
,W/ProcessCpuTracker(  891): Skipping unknown process pid 7822
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4341, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1704): Connected
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
D/GCM     ( 1704): Message class com.google.f.a.a.p
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6774): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6774): [hasSamungAccount] - No Samsung Account,
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CSTORAGE( 6774): ================================================
I/CSTORAGE( 6774):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6774): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6774): [GetString-S]
E/art     ( 6774): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6774): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6774): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6774): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6774): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6774): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6774): [ensureRegistration] - No Samsung account
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/dhcpcd  ( 7555): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  279): DCD ON
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/PreloadUpdateManagerStateMachine( 7133): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7133): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7133): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7133): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7133): RestApi Request Add : 2307
,E/File    ( 7133): fail readDirectory() errno=2
,I/dhcpcd  ( 7555): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 7555): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine( 7133): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/System.out( 7133): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 7133): (HTTPLog)-Static: isShipBuild true
,I/System.out( 7133): (HTTPLog)-Thread-1185-408916487: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 7133): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7133, getuid(): 10040
,I/qtaguid ( 7133): Untagging socket 26
,D/hcjo    ( 7133): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 7133): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 7133): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7133): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7133): entry::REQ_UPDATE_CHECK
,I/Volley  ( 7133): RestApi Request Add : 2315
,I/qtaguid ( 7133): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7133, getuid(): 10040
,I/qtaguid ( 7133): Untagging socket -1
,I/qtaguid ( 7133): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 7133): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 7133): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 7133): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 7133): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 7133): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7133): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7133): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 7133): exit::FINISH
D/PreloadUpdateManagerStateMachine( 7133): entry::IDLE
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/FactoryTest( 6464): Not factory mode
D/FactoryTest( 6464): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6464): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 6464): still no open session command from host, so toast
,W/ContextImpl( 6464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 6464): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6464): Timeline: Activity_launch_request id:com.android.settings time:114813
,E/PersonaManagerService(  891): inState():  stateMachine is null !!
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  891): mDVFSHelper.acquire()
,I/SQLiteSecureOpenHelper( 3591): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3591): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/MTPRx   ( 6464): started activity for popup
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager( 6464): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6464): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6464): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6464): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6464): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6464): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6464): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6464): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6464): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,E/ActivityManager(  891): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  891): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@29b7731 attribute=null, token = android.os.BinderProxy@125651a5
,I/SQLiteSecureOpenHelper( 3591): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3591): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6464): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6464): dev.kiessupport is : TRUE
,D/Activity( 6464): performCreate Call secproduct feature valuefalse
D/Activity( 6464): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ActivityManager(  891): post active user change for 0
D/KnoxTimeoutHandler(  891): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  891): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/Timeline( 7332): Timeline: Activity_idle id: android.os.BinderProxy@2c570cfd time:115039
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:m  (  891): SIOP:: AP = 360, PST = 406, CUR = 300
,D/X       (  891): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1228):  LEVEL : -1
,E/TranscodeReceiver( 7150): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7150):  SIOP_LEVEL: -1
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4355, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6668): [1] 5.onFinished: Scheduling replication attempt 3.
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  891): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  891): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/CustomFrequencyManagerService(  891): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 891  tag : ACTIVITY_RESUME_BOOSTER@10
,I/ActivityManager(  891): Waited long enough for: ServiceRecord{3f9ed8bc u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  279): DCD ON
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:m  (  891): SIOP:: AP = 340, PST = 393, CUR = 300
,E/SMD     (  279): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  279): DCD ON
,D/PowerManagerService(  891): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  891): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  891): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  891): lcd : 37 +
,D/lights  (  891): lcd : 37 -
,D/lights  (  891): lcd : 29 +
,D/lights  (  891): lcd : 29 -
,D/lights  (  891): lcd : 21 +
,D/lights  (  891): lcd : 21 -
,D/DisplayPowerController(  891): getFinalBrightness : 15 -> 15
,D/lights  (  891): lcd : 15 +
,D/lights  (  891): lcd : 15 -
,D/DisplayPowerController(  891): getFinalBrightness : 15 -> 15
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  279): DCD ON
,E/Watchdog(  891): !@Sync 4
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  891): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  891): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): applyOpen
,D/StatusBar.NetworkController( 1172): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): applyOpen
,E/SMD     (  279): DCD ON
,D/PowerManagerService(  891): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  891): Nap time (uid 1000)...
I/PowerManagerService(  891): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  891): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  891): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  891): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  891): setDeviceInteractive: 0
D/PowerManagerService(  891): handleSandman : startDream()
,D/InputManager-JNI(  891): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  891): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  891): Sleeping (uid 1000)...
D/InputManager-JNI(  891): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  891): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  891): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  891): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  891): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  891): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  891): 	.unregisterCallback : 1, client=
D/SContextService(  891): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3717caa2, Service = Auto Rotation, used = 1
,W/CAE     (  891): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  891): stop(ContextProvider.java:149)
,V/CAE     (  891): clear(AutoRotationRunner.java:182)
,V/CAE     (  891): disable(AutoRotationRunner.java:171)
,I/CAE     (  891): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  891): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  294): sendContextData: -78, 7, 0, 0
,D/CAE     (  891): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  891): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  891): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  891): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  891): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  891): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  891): removeSContextService() : service = Auto Rotation
D/SContextService(  891): ===== SContext Service List =====
D/SContextManager(  891):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@284b8085, service=Auto Rotation
D/KeyguardViewMediator( 1172): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1172): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1172): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1172): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3591): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3591): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/KeyguardViewMediator( 1172): timeout : 5000
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/DisplayPowerController(  891): ColorFade: onAnimationStart
D/DisplayPowerController(  891): getFinalBrightness : 42 -> 0
,D/lights  (  891): lcd : 13 +
,D/lights  (  891): lcd : 13 -
,D/lights  (  891): lcd : 4 +
,D/KeyguardViewMediator( 1172): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1172): handleNotifyScreenOff
,D/lights  (  891): lcd : 4 -
,D/DisplayPowerController(  891): getFinalBrightness : 42 -> 0
,D/lights  (  891): lcd : 0 +
,D/LightsService(  891): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 891) 
D/LightsService(  891): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 25
,D/lights  (  891): lcd : 0 -
,D/SensorManager(  891): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  891): unregisterListener ::   
D/lights  (  891): led_pattern : 5 +
,D/BatteryService(  891): turn on LED for fully charged
,D/lights  (  891): led_pattern : 5 -
D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  891): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  891): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  891): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  891): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  294): sendContextData: -76, 13, -46, 0
,I/CAE     (  891): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 10, 50, 54,
D/SensorHubManager(  891): SendSensorHubData: send data = -63, 14, 10, 50, 54
,D/Sensorhubs(  294): sendContextData: -63, 14, 10, 50, 54
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  891):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  891): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  891): handleScreenStateChanged Exit: false
,D/NotificationService(  891): ACTION_SCREEN_OFF
,D/LightsService(  891): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 891) 
D/LightsService(  891): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
E/WifiStateMachine(  891): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 25
E/WifiStateMachine(  891): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  891): do suspend true
,D/SensorManager(  891): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  891): unregisterListener ::   
D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  287): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  287): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  891): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  891): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  891): Bridge Server is not available
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1172): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1172): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1172): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  891): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  891): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1447): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1172):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1172): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1172): dismissHelpPopup 
,D/accuweather( 2200): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2200): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2200): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  891): !@ ColorFade entry
D/DisplayPowerController(  891): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  891): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  891): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  891): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  891): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  891): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  891): unregisterListener ::   
,E/Sensors (  891): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  891): unregisterListener ::   
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/DisplayPowerController(  891): getFinalBrightness : 0 -> 0
D/DisplayPowerController(  891): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  891): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  891): Display changed displayId=0
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
,D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,W/ActivityManager(  891): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  891): SIOP:: AP = 320, PST = 377, CUR = 300
,W/ActivityManager(  891): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/PowerManagerService(  891): [PWL] sb release: PowerManagerService.Broadcasts
D/LockPatternUtilsCache( 1172): value : false
,D/StatusBar.NetworkController( 1172): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/rmt_storage(  267): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  267): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  267): wakelock acquired: 1, error no: 42
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  267): 
,I/rmt_storage(  267): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/SurfaceControl(  891): Excessive delay in setPowerMode(): 254ms
D/PowerManagerService(  891): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  891): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  891): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  891): Got set_interactive hint
,I/PowerManagerService(  891): [PWL] Off : 0s ago
I/PowerManagerService(  891): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  891): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  891): getFinalBrightness : 0 -> 0
D/PowerManagerService(  891): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  891): [PWL] sb release: PowerManagerService.Display
,V/AlarmManager(  891): waitForAlarm result :4
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6668): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardViewMediator( 1172): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/KeyguardViewMediator( 1172): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  891): [PWL] Off : 5s ago
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 320, PST = 365, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1704): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6641): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at kff.l(PG:132)
E/HttpOperation( 6641): 	at dsf.a(PG:807)
E/HttpOperation( 6641): 	at fhk.a(PG:1126)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 8 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 10 more
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6641): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at kff.l(PG:132)
E/HttpOperation( 6641): 	at ieo.a(PG:43)
E/HttpOperation( 6641): 	at iep.a(PG:93)
E/HttpOperation( 6641): 	at fhn.a(PG:59)
E/HttpOperation( 6641): 	at lex.a(PG:85)
E/HttpOperation( 6641): 	at lex.b(PG:132)
E/HttpOperation( 6641): 	at fhk.a(PG:1146)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 12 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 14 more
,E/ExperimentLoader( 6641): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6641): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6641): 	at kfv.a(PG:65)
E/ExperimentLoader( 6641): 	at kff.u(PG:385)
E/ExperimentLoader( 6641): 	at kfb.a(PG:29)
E/ExperimentLoader( 6641): 	at kff.l(PG:132)
E/ExperimentLoader( 6641): 	at ieo.a(PG:43)
E/ExperimentLoader( 6641): 	at iep.a(PG:93)
E/ExperimentLoader( 6641): 	at fhn.a(PG:59)
E/ExperimentLoader( 6641): 	at lex.a(PG:85)
E/ExperimentLoader( 6641): 	at lex.b(PG:132)
E/ExperimentLoader( 6641): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6641): 	at fhk.a(PG:908)
E/ExperimentLoader( 6641): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6641): 	at ihi.a(PG:22)
E/ExperimentLoader( 6641): 	at kft.a(PG:91)
E/ExperimentLoader( 6641): 	at kfv.a(PG:62)
E/ExperimentLoader( 6641): 	... 12 more
E/ExperimentLoader( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6641): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6641): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6641): 	at ihi.a(PG:19)
E/ExperimentLoader( 6641): 	... 14 more
I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/PowerManagerService(  891): [PWL] Off : 15s ago
I/PowerManagerService(  891): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  891): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  891): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=891, ws=WorkSource{10135}) (elapsedTime=414)
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 31258(1860KB) AllocSpace objects, 17(1377KB) LOS objects, 39% free, 17MB/29MB, paused 3.475ms total 145.848ms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1704): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6641): [getaccountstatus] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at ixd.a(PG:248)
E/HttpOperation( 6641): 	at ixd.b(PG:206)
E/HttpOperation( 6641): 	at ixd.a(PG:175)
E/HttpOperation( 6641): 	at fig.a(PG:78)
E/HttpOperation( 6641): 	at lex.a(PG:85)
E/HttpOperation( 6641): 	at lex.b(PG:132)
E/HttpOperation( 6641): 	at fhk.a(PG:1146)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 12 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 14 more
,E/EsSyncAdapterService( 6641): Sync failure
E/EsSyncAdapterService( 6641): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6641): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6641): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6641): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6641): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6641): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6641): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6641): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6641): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6641): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6641): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6641): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6641): 	... 10 more
E/EsSyncAdapterService( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6641): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6641): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6641): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6641): 	... 12 more
E/EsSyncAdapterService( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6641): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6641): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6641): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6641): 	... 14 more
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 122634, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 310, PST = 356, CUR = 300
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :4
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6668): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6668): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  279): DCD ON
,E/Watchdog(  891): !@Sync 5
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 310, PST = 347, CUR = 300
,I/PowerManagerService(  891): [PWL] Off : 30s ago
,E/SMD     (  279): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 300, PST = 337, CUR = 300
,V/AlarmManager(  891): waitForAlarm result :4
,E/SMD     (  279): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1704): Vacuum at: now=1452509496321 tag=VacuumService
,I/GoogleURLConnFactory( 1704): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1704): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1704): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/System.out( 1704): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1704): (HTTPLog)-Static: isShipBuild true
I/System.out( 1704): (HTTPLog)-Thread-203-651373026: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1704): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1704, getuid(): 10012
,I/qtaguid ( 1704): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1704, getuid(): 10012
,I/art     (  891): Explicit concurrent mark sweep GC freed 70122(3MB) AllocSpace objects, 34(3MB) LOS objects, 29% free, 38MB/54MB, paused 1.807ms total 151.697ms
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6668): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1704): No account for auth token provided
,I/qtaguid ( 1704): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1704, getuid(): 10012
,W/Uploader( 1704): No account for auth token provided
,I/qtaguid ( 1704): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1704, getuid(): 10012
,W/Uploader( 1704): No account for auth token provided
,I/qtaguid ( 1704): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1704, getuid(): 10012
,W/Uploader( 1704):  no longer exists, so no auth token.
,I/qtaguid ( 1704): Tagging socket 56 with tag 120100000000{4609,0} uid -1, pid: 1704, getuid(): 10012
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7268): Starting books sync, d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1704): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532125646415159400&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532125646415159400&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532125646415159400&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/BooksSync( 7268): Soft error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532125646415159400&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7268): Sync error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7532125646415159400&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7268): Finished books sync
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159202, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6641): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at kff.l(PG:132)
E/HttpOperation( 6641): 	at dsf.a(PG:807)
E/HttpOperation( 6641): 	at fhk.a(PG:1126)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 8 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 10 more
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,E/HttpOperation( 6641): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at kff.l(PG:132)
E/HttpOperation( 6641): 	at ieo.a(PG:43)
E/HttpOperation( 6641): 	at iep.a(PG:93)
E/HttpOperation( 6641): 	at fhn.a(PG:59)
E/HttpOperation( 6641): 	at lex.a(PG:85)
E/HttpOperation( 6641): 	at lex.b(PG:132)
E/HttpOperation( 6641): 	at fhk.a(PG:1146)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 12 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 14 more
,E/ExperimentLoader( 6641): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6641): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6641): 	at kfv.a(PG:65)
E/ExperimentLoader( 6641): 	at kff.u(PG:385)
E/ExperimentLoader( 6641): 	at kfb.a(PG:29)
E/ExperimentLoader( 6641): 	at kff.l(PG:132)
E/ExperimentLoader( 6641): 	at ieo.a(PG:43)
E/ExperimentLoader( 6641): 	at iep.a(PG:93)
E/ExperimentLoader( 6641): 	at fhn.a(PG:59)
E/ExperimentLoader( 6641): 	at lex.a(PG:85)
E/ExperimentLoader( 6641): 	at lex.b(PG:132)
E/ExperimentLoader( 6641): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6641): 	at fhk.a(PG:908)
E/ExperimentLoader( 6641): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6641): 	at ihi.a(PG:22)
E/ExperimentLoader( 6641): 	at kft.a(PG:91)
E/ExperimentLoader( 6641): 	at kfv.a(PG:62)
E/ExperimentLoader( 6641): 	... 12 more
E/ExperimentLoader( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6641): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6641): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6641): 	at ihi.a(PG:19)
E/ExperimentLoader( 6641): 	... 14 more
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6641): [getaccountstatus] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at ixd.a(PG:248)
E/HttpOperation( 6641): 	at ixd.b(PG:206)
E/HttpOperation( 6641): 	at ixd.a(PG:175)
E/HttpOperation( 6641): 	at fig.a(PG:78)
E/HttpOperation( 6641): 	at lex.a(PG:85)
E/HttpOperation( 6641): 	at lex.b(PG:132)
E/HttpOperation( 6641): 	at fhk.a(PG:1146)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 12 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 14 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/EsSyncAdapterService( 6641): Sync failure
E/EsSyncAdapterService( 6641): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6641): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6641): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6641): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6641): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6641): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6641): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6641): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6641): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6641): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6641): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6641): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6641): 	... 10 more
E/EsSyncAdapterService( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6641): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6641): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6641): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6641): 	... 12 more
E/EsSyncAdapterService( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6641): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6641): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6641): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6641): 	... 14 more
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 185245, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  891): SIOP:: AP = 300, PST = 331, CUR = 300
,I/PowerManagerService(  891): [PWL] Off : 50s ago
,E/SMD     (  279): DCD ON
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,E/Watchdog(  891): !@Sync 6
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 300, PST = 326, CUR = 300
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 315, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  891): [PWL] Off : 75s ago
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 308, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  891): stay LED for fully charged
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,E/Watchdog(  891): !@Sync 7
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 303, CUR = 300
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  279): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 300, CUR = 300
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  891): [PWL] Off : 105s ago
,I/PowerManagerService(  891): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  891): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  891): [PWL]       PARTIAL_WAKE_LOCK              'SyncManagerHandleSyncAlarm' (uid=1000, pid=891, ws=null) (elapsedTime=55)
I/PowerManagerService(  891): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=891, ws=null) (elapsedTime=29)
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7268): Starting books sync, d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7683401524361166843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7683401524361166843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  279): DCD ON
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7683401524361166843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7268): Soft error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7683401524361166843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7268): Sync error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-7683401524361166843&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7268): Finished books sync
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 217679, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  891): Explicit concurrent mark sweep GC freed 46745(2MB) AllocSpace objects, 31(1081KB) LOS objects, 29% free, 37MB/53MB, paused 1.788ms total 205.243ms
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 297, CUR = 300
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  279): DCD ON
,E/Watchdog(  891): !@Sync 8
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  279): DCD ON,
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 59433(3MB) AllocSpace objects, 64(4MB) LOS objects, 40% free, 18MB/30MB, paused 1.693ms total 145.475ms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1704): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6641): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at kff.l(PG:132)
E/HttpOperation( 6641): 	at dsf.a(PG:807)
E/HttpOperation( 6641): 	at fhk.a(PG:1126)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 8 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 10 more
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6641): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at kff.l(PG:132)
E/HttpOperation( 6641): 	at ieo.a(PG:43)
E/HttpOperation( 6641): 	at iep.a(PG:93)
E/HttpOperation( 6641): 	at fhn.a(PG:59)
E/HttpOperation( 6641): 	at lex.a(PG:85)
E/HttpOperation( 6641): 	at lex.b(PG:132)
E/HttpOperation( 6641): 	at fhk.a(PG:1146)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 12 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 14 more
E/ExperimentLoader( 6641): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6641): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6641): 	at kfv.a(PG:65)
E/ExperimentLoader( 6641): 	at kff.u(PG:385)
E/ExperimentLoader( 6641): 	at kfb.a(PG:29)
E/ExperimentLoader( 6641): 	at kff.l(PG:132)
E/ExperimentLoader( 6641): 	at ieo.a(PG:43)
E/ExperimentLoader( 6641): 	at iep.a(PG:93)
E/ExperimentLoader( 6641): 	at fhn.a(PG:59)
E/ExperimentLoader( 6641): 	at lex.a(PG:85)
E/ExperimentLoader( 6641): 	at lex.b(PG:132)
E/ExperimentLoader( 6641): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6641): 	at fhk.a(PG:908)
E/ExperimentLoader( 6641): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6641): 	at ihi.a(PG:22)
E/ExperimentLoader( 6641): 	at kft.a(PG:91)
E/ExperimentLoader( 6641): 	at kfv.a(PG:62)
E/ExperimentLoader( 6641): 	... 12 more
E/ExperimentLoader( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6641): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6641): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6641): 	at ihi.a(PG:19)
E/ExperimentLoader( 6641): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6641): [getaccountstatus] Unexpected exception
E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6641): 	at kfv.a(PG:65)
E/HttpOperation( 6641): 	at kff.u(PG:385)
E/HttpOperation( 6641): 	at kfb.a(PG:29)
E/HttpOperation( 6641): 	at ixd.a(PG:248)
E/HttpOperation( 6641): 	at ixd.b(PG:206)
E/HttpOperation( 6641): 	at ixd.a(PG:175)
E/HttpOperation( 6641): 	at fig.a(PG:78)
E/HttpOperation( 6641): 	at lex.a(PG:85)
E/HttpOperation( 6641): 	at lex.b(PG:132)
E/HttpOperation( 6641): 	at fhk.a(PG:1146)
E/HttpOperation( 6641): 	at fhk.a(PG:908)
E/HttpOperation( 6641): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6641): 	at ihi.a(PG:22)
E/HttpOperation( 6641): 	at kft.a(PG:91)
E/HttpOperation( 6641): 	at kfv.a(PG:62)
E/HttpOperation( 6641): 	... 12 more
E/HttpOperation( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6641): 	at gde.c(Unknown Source)
E/HttpOperation( 6641): 	at gde.b(Unknown Source)
E/HttpOperation( 6641): 	at ihi.a(PG:19)
E/HttpOperation( 6641): 	... 14 more
,E/EsSyncAdapterService( 6641): Sync failure
E/EsSyncAdapterService( 6641): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6641): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6641): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6641): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6641): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6641): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6641): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6641): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6641): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6641): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6641): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6641): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6641): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6641): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6641): 	... 10 more
E/EsSyncAdapterService( 6641): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6641): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6641): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6641): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6641): 	... 12 more
E/EsSyncAdapterService( 6641): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6641): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6641): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6641): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6641): 	... 14 more
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): There is/are notification(s) 
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 252185, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  279): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 140s ago
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  279): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,E/Watchdog(  891): !@Sync 9
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  279): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  279): DCD ON
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 290, CUR = 300,
,E/SMD     (  279): DCD ON
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  891): initializing...
,I/TLC_TIMA_PKM_initialize(  891): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  891): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  891): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  891): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  891): App is not loaded in QSEE
,D/QSEECOMAPI: (  891): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  891): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  891): Trustlet response is completed
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  279): DCD ON
,E/Watchdog(  891): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  279): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 180s ago
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  279): DCD ON
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  279): DCD ON
,E/SMD     (  279): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  891): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  891):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1172):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7268): Starting books sync, d
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1704): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/PhoneStatusBar( 1172): Icon Only
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1296124703207776060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  891): waitForAlarm result :4
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0,
,I/ActivityManager(  891): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8148 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 8148): MountEmulatedStorage()
,E/Zygote  ( 8148): v2
,I/libpersona( 8148): KNOX_SDCARD checking this for 10081
,I/libpersona( 8148): KNOX_SDCARD not a persona
,I/SELinux ( 8148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8148): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/art     (  310): Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 8.271ms total 80.594ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 1.778ms total 26.068ms
,D/TimaKeyStoreProvider( 8148): TimaSignature is unavailable
,D/ActivityThread( 8148): Added TimaKeyStore provider
,D/ResourcesManager( 8148): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 1.331ms total 42.762ms
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  279): DCD ON
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1296124703207776060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1704): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  891): uri = 14 selection = getSealedState
,D/SecContentProvider2(  891): mCursor = null
,D/SecContentProvider2(  891): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  891): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1172): Icon Only
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): There is/are notification(s) 
,W/GLSActivity( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1704): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1704): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1704): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1704): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7268): Authentication error
E/BooksAccountManager( 7268): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7268): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7268): null auth token
,I/qtaguid ( 7268): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7268, getuid(): 10082
,I/qtaguid ( 7268): Untagging socket 34
,W/ApiaryClient( 7268): Error response from books API: {
W/ApiaryClient( 7268):  "error": {
W/ApiaryClient( 7268):   "errors": [
W/ApiaryClient( 7268):    {
W/ApiaryClient( 7268):     "domain": "global",
W/ApiaryClient( 7268):     "reason": "required",
W/ApiaryClient( 7268):     "message": "Login Required",
W/ApiaryClient( 7268):     "locationType": "header",
W/ApiaryClient( 7268):     "location": "Authorization"
W/ApiaryClient( 7268):    }
W/ApiaryClient( 7268):   ],
W/ApiaryClient( 7268):   "code": 401,
W/ApiaryClient( 7268):   "message": "Login Required"
W/ApiaryClient( 7268):  }
W/ApiaryClient( 7268): }
,W/ApiaryClient( 7268): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1296124703207776060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7268): Headers suppressed
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7268): Soft error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1296124703207776060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7268): Sync error
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7268): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1296124703207776060&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7268): Headers suppressed
E/BooksSync( 7268): 
E/BooksSync( 7268): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7268): Finished books sync
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  891): Killing 6253:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,D/SyncManager(  891): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 309566, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  891): mCursor = null
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_6253/cgroup.procs: No such file or directory
,E/SMD     (  279): DCD ON
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:m  (  891): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/jxcore-log( 7332): --= Surplus to requirements =--
I/jxcore-log( 7332): 
,I/jxcore-log( 7332): ****TEST TOOK:  ms ****
I/jxcore-log( 7332): 
I/jxcore-log( 7332): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7332): 
,D/AndroidRuntime( 8226): 
D/AndroidRuntime( 8226): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8226): CheckJNI is OFF
,D/AndroidRuntime( 8226): setted country_code = Germany
,D/AndroidRuntime( 8226): setted countryiso_code = DE
,D/AndroidRuntime( 8226): setted sales_code = DBT
,D/AndroidRuntime( 8226): readGMSProperty: start
D/AndroidRuntime( 8226): readGMSProperty: already setted!!
D/AndroidRuntime( 8226): readGMSProperty: end
D/AndroidRuntime( 8226): addProductProperty: start
,E/SMD     (  279): DCD ON
,E/AffinityControl( 8226): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8226): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  891): START PACKAGE DELETE: observer{783078385}
D/PackageManager(  891): pkg{<packageName>}
D/PackageManager(  891): user{0}
D/PackageManager(  891): caller{2000}
D/PackageManager(  891): flags{3}
,D/PersonaManagerService(  891): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  891): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  891): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  891): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  891): !@killApplicatoin: 10367, uninstall pkg
,I/ActivityManager(  891): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
,I/ActivityManager(  891): Killing 7332:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
,I/ActivityManager(  891):   Force finishing activity ActivityRecord{2f6b1e3f u0 com.test.thalitest/.MainActivity t12}
,D/FocusedStackFrame(  891): Set to : 0
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1172): value : false
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/PackageSettings(  891): Skipping PackageSetting{258f939e com.example.hello/10375} due to missing metadata
,D/WifiService(  891): Client connection lost with reason: 4
,D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  891): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
,I/art     ( 1561): Explicit concurrent mark sweep GC freed 39135(2MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 433us total 41.259ms
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1873): mOCRHelper is null
,E/libprocessgroup(  891): failed to kill 1 processes for processgroup 7332
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 2127): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4697): Explicit concurrent mark sweep GC freed 4028(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 1.733ms total 165.934ms
,I/KLMS-2.4.503: ( 7510): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7510): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452509658436
,I/KLMS-2.4.503: ( 7510): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 7510): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager( 2859): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/art     (  891): Explicit concurrent mark sweep GC freed 41486(2MB) AllocSpace objects, 44(1094KB) LOS objects, 29% free, 38MB/54MB, paused 16.212ms total 218.010ms
I/art     (  891): WaitForGcToComplete blocked for 122.782ms for cause Explicit
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 2859): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/RegisteredServicesCache( 1447): empty dynamic service
,D/EnterpriseDeviceManagerService(  891): Package has changed for user 0
D/EnterpriseDeviceManagerService(  891): Admin package name: com.google.android.gms
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8255): MountEmulatedStorage()
E/Zygote  ( 8255): v2
I/libpersona( 8255): KNOX_SDCARD checking this for 10104
I/libpersona( 8255): KNOX_SDCARD not a persona
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ActivityManager(  891): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8255 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,I/SELinux ( 8255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SELinux ( 8255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/TimaKeyStoreProvider( 8255): TimaSignature is unavailable
,D/ActivityThread( 8255): Added TimaKeyStore provider
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8255): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/SurfaceWidgetView( 1488): destroyHardwareResources():132540807
,V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  891): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/Launcher( 1488): onRestart, Launcher: 110762684
,D/Launcher( 1488): onStart, Launcher: 110762684
D/Launcher.HomeView( 1488): onStart
,D/elm:14451( 8255): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8255): ELMEngine.ELMEngine( context ).
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2200): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2200): [237392/6] SurfaceWidget drawing first frame
D/elm:14451( 8255): MDMBridge.setEnterpriseBridge()
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/elm:14451( 8255): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8273): MountEmulatedStorage()
E/Zygote  ( 8273): v2
I/libpersona( 8273): KNOX_SDCARD checking this for 10017
I/libpersona( 8273): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8273 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/elm:14451( 8255): ElmAgentService : onCreate()
,D/elm:14451( 8255): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8255): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8255): MDMBridge.getInstance()
,D/elm:14451( 8255): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux ( 8273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,I/SELinux ( 8273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14451( 8255): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/InputMethodManagerService(  891): Got RemoteException sending setActive(false) notification to pid 7332 uid 10367
,D/TimaKeyStoreProvider( 8273): TimaSignature is unavailable
,D/ActivityThread( 8273): Added TimaKeyStore provider
W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:14451( 8255): ElmAgentService : onDestroy().
I/ActivityManager(  891): Killing 6877:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/RCPManagerService(  891): PackageReceiver onReceive()
I/HarmonyEASService(  891): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  891): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  891): uID is 10367
V/EnterpriseBillingPolicy(  891): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - end - null
D/ResourcesManager( 8273): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,I/art     (  891): Explicit concurrent mark sweep GC freed 13793(710KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 38MB/54MB, paused 5.659ms total 285.194ms
D/TaskPersister(  891): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  891): removeObsoleteFile: deleting file=12_task_thumbnail.png
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
,D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8273): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8273): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8273): onReceive() : package name is not s health. Return !!!
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{3a456b1b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:341447
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 6774): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6774): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6774): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6774): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/PackageManager(  891): delete codoeFile: 
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/PackageManager(  891): result of delete: 1{783078385}
D/LockPatternUtilsCache( 1172): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1172): value : false
E/Zygote  ( 8293): MountEmulatedStorage()
E/Zygote  ( 8293): v2
I/libpersona( 8293): KNOX_SDCARD checking this for 10034
I/libpersona( 8293): KNOX_SDCARD not a persona
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
I/ActivityManager(  891): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8293 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  891): Killing 6929:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 8293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  891): failed to open /acct/uid_10098/pid_6877/cgroup.procs: No such file or directory
I/SELinux ( 8293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 8226): Shutting down VM
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/TimaKeyStoreProvider( 8293): TimaSignature is unavailable
D/ActivityThread( 8293): Added TimaKeyStore provider
D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/libprocessgroup(  891): failed to open /acct/uid_10033/pid_6929/cgroup.procs: No such file or directory
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(  891): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  891): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/FeatureConfig( 8293): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  891): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  891): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8293): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8293): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 8293): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 8293): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8310): MountEmulatedStorage()
,E/Zygote  ( 8310): v2
I/libpersona( 8310): KNOX_SDCARD checking this for 10035
I/libpersona( 8310): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8310 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6905:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/SELinux ( 8310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8310): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/libprocessgroup(  891): failed to open /acct/uid_10099/pid_6905/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 8310): TimaSignature is unavailable
,D/ActivityThread( 8310): Added TimaKeyStore provider
,D/ResourcesManager( 8310): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,F/libc    ( 8310): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3d0a000 in tid 8310 (oid.app.shealth)
,E/audit_log( 2047): File locking failed. error= Bad file number
,E/audit_log( 2047): File locking failed. error= Bad file number
,I/ActivityManager(  891): Process com.sec.android.app.shealth (pid 8310)(adj 0) has died(211,535)
,I/EventHub(  891): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 5335): Fatal signal 7 (SIGBUS), code 2, fault addr 0x781e4a00 in tid 5335 (om.sec.spp.push)
,F/libc    ( 5335): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2047): File locking failed. error= Bad file number
,I/Zygote  (  310): Process 8310 exited due to signal (7)
,I/ActivityManager(  891): Process com.sec.spp.push (pid 5335)(adj 0) has died(215,535)
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/EventHub(  891): Removing device '/dev/input/event5' due to inotify event
,E/Zygote  ( 8330): MountEmulatedStorage()
E/Zygote  ( 8330): v2
I/libpersona( 8330): KNOX_SDCARD checking this for 10038
I/libpersona( 8330): KNOX_SDCARD not a persona
,I/Zygote  (  310): Process 5335 exited due to signal (7)
,I/ActivityManager(  891): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8330 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8330): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8330): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  891): Removing device '/dev/input/event6' due to inotify event
,D/TimaKeyStoreProvider( 8330): TimaSignature is unavailable
,D/ActivityThread( 8330): Added TimaKeyStore provider
,D/ResourcesManager( 8330): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8330): Unable to create files subdir /data/data/com.sec.spp.push/cache
,E/ActivityThread( 8330): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  891): Removing device '/dev/input/event7' due to inotify event
,E/SPPClientService( 8330): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8330): [PushClientApplication] Push log off : This is Ship build version
,W/ContextImpl( 8330): Unable to create files subdir /data/data/com.sec.spp.push/files
,D/SPPClientService( 8330): PushLog.txt file is not deleted.
W/ContextImpl( 8330): Unable to create files subdir /data/data/com.sec.spp.push/files
,D/SPPClientService( 8330): PushLog.txt file is not deleted.
D/SPPClientService( 8330): ============PushLog. stop!
,F/libc    ( 8330): Fatal signal 7 (SIGBUS), code 2, fault addr 0x781d4018 in tid 8330 (moteNotiProcess)
,F/libc    ( 8330): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2047): File locking failed. error= Bad file number
,I/ActivityManager(  891): Process com.sec.spp.push:RemoteNotiProcess (pid 8330)(adj 0) has died(215,535)
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8346): MountEmulatedStorage()
,E/Zygote  ( 8346): v2
,I/libpersona( 8346): KNOX_SDCARD checking this for 10042
,I/libpersona( 8346): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8346 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/EventHub(  891): Removing device '/dev/input/event8' due to inotify event
,I/Zygote  (  310): Process 8330 exited due to signal (7)
,I/EventHub(  891): Removing device '/dev/input/event9' due to inotify event
,I/SELinux ( 8346): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8346): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8346): TimaSignature is unavailable
,D/ActivityThread( 8346): Added TimaKeyStore provider
,D/ResourcesManager( 8346): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 8346): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8346): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ContextImpl( 8346): Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
E/ActivityThread( 8346): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8346): Fatal signal 7 (SIGBUS), code 2, fault addr 0xaf87a000 in tid 8346 (sdk.samsunglink)
,F/libc    ( 8346): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2047): File locking failed. error= Bad file number
,I/EventHub(  891): Removing device '/dev/input/event10' due to inotify event
,I/ActivityManager(  891): Process com.samsung.android.sdk.samsunglink (pid 8346)(adj 0) has died(215,536)
,I/SA      ( 6816): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6816): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10367 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,F/libc    ( 1805): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77e0044c in tid 1805 (d.process.acore)
,F/libc    ( 1805): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2047): File locking failed. error= Bad file number
,I/ActivityManager(  891): Process android.process.acore (pid 1805)(adj 0) has died(220,536)
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,I/Zygote  (  310): Process 8346 exited due to signal (7)
,E/Zygote  ( 8366): MountEmulatedStorage()
E/Zygote  ( 8366): v2
I/libpersona( 8366): KNOX_SDCARD checking this for 10048
I/libpersona( 8366): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8366 uid=10048 gids={50048, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/EventHub(  891): Removing device '/dev/input/event11' due to inotify event
,I/Zygote  (  310): Process 1805 exited due to signal (7)
,I/SELinux ( 8366): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8366): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8366): TimaSignature is unavailable
,D/ActivityThread( 8366): Added TimaKeyStore provider
,D/ResourcesManager( 8366): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 8366): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8366): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8366): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8366): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8366): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 8366): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8366): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8366): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 8366): Unable to create files subdir /data/data/com.sec.android.gallery3d/cache
,E/ActivityThread( 8366): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8366): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3a2f000 in tid 8366 (droid.gallery3d)
,F/libc    ( 8366): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2047): File locking failed. error= Bad file number
,I/ActivityManager(  891): Process com.sec.android.gallery3d (pid 8366)(adj 0) has died(220,536)
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8381): MountEmulatedStorage()
,E/Zygote  ( 8381): v2
I/libpersona( 8381): KNOX_SDCARD checking this for 10050
I/libpersona( 8381): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8381 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/Zygote  (  310): Process 8366 exited due to signal (7)
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/SELinux ( 8381): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8381): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8381): TimaSignature is unavailable
,D/ActivityThread( 8381): Added TimaKeyStore provider

```
