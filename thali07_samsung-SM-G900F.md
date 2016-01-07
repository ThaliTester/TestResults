#### Test 55311151a2306df_thali07_samsung-SM-G900F Logs


```
--------- beginning of system
D/PowerManagerService(  890): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1170 (0x0)
--------- beginning of main
I/qtaguid ( 7356): Untagging socket 34
W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4987405110241113019&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/GAV2    ( 7356): Thread[GAThread,5,main]: No campaign data found.
V/AlarmManager(  890): waitForAlarm result :4
D/SSRM:m  (  890): SIOP:: AP = 340, PST = 418, CUR = 300
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SMD     (  287): DCD ON
I/art     ( 1669): Explicit concurrent mark sweep GC freed 23531(1489KB) AllocSpace objects, 14(1134KB) LOS objects, 40% free, 17MB/29MB, paused 478us total 32.648ms
D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 2.
D/AndroidRuntime( 7396): 
D/AndroidRuntime( 7396): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7396): CheckJNI is OFF
D/AndroidRuntime( 7396): setted country_code = Germany
D/AndroidRuntime( 7396): setted countryiso_code = DE
D/AndroidRuntime( 7396): setted sales_code = DBT
D/AndroidRuntime( 7396): readGMSProperty: start
D/AndroidRuntime( 7396): readGMSProperty: already setted!!
D/AndroidRuntime( 7396): readGMSProperty: end
D/AndroidRuntime( 7396): addProductProperty: start
V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1669): creating new AssetManager and set to /system/app/Books/Books.apk
V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
I/qtaguid ( 7356): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
E/AffinityControl( 7396): AffinityControl: registerfunction enter
D/AndroidRuntime( 7396): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  890): inState():  stateMachine is null !!
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  890): mDVFSHelper.acquire()
I/qtaguid ( 7356): Untagging socket 34
W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4987405110241113019&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  252): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
I/SQLiteSecureOpenHelper( 3563): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3563): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/AndroidRuntime( 7396): Shutting down VM
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/DBG_DM  ( 3800): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 46
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/DBG_DM  ( 3800): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3800): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3800): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3800): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/LightsService(  890): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
D/LightsService(  890): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PhoneStatusBar( 1170): Icon Only
D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3800): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3800): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
E/Zygote  ( 7427): MountEmulatedStorage()
E/Zygote  ( 7427): v2
I/libpersona( 7427): KNOX_SDCARD checking this for 10367
D/KnoxNotification( 1170): ----- inflateViews : modified publicViewLocal -----
I/libpersona( 7427): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7427 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7427): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 1170): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1170): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1170): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@18cb6472
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
D/TimaKeyStoreProvider( 7427): TimaSignature is unavailable
D/ActivityThread( 7427): Added TimaKeyStore provider
V/ActivityManager(  890): Display changed displayId=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 7427): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
I/WebViewFactory( 7427): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7427): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7427): Loading: webviewchromium
,I/LibraryLoader( 7427): Time to load native libraries: 2 ms (timestamps 8453-8455)
,I/LibraryLoader( 7427): Expected native library version number "",actual native library version number ""
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/WebViewChromiumFactoryProvider( 7427): Binding Chromium to main looper Looper (main, tid 1) {183b605d}
I/LibraryLoader( 7427): Expected native library version number "",actual native library version number ""
I/chromium( 7427): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/BrowserStartupController( 7427): Initializing chromium process, renderers=0
W/art     ( 7427): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7427): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7427): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7427): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Adreno-EGL( 7427): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7427): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7427): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7427): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7427): Remote Branch: 
I/Adreno-EGL( 7427): Local Patches: 
I/Adreno-EGL( 7427): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/chromium( 7427): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7427): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/art     ( 7427): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7427): onDetachedFromWindow called when already detached. Ignoring
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/SystemWebViewEngine( 7427): CordovaWebView is running on device made by: samsung
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/art     ( 7427): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7427): Attempt to remove local handle scope entry from IRT, ignoring
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/Activity( 7427): performCreate Call secproduct feature valuefalse
,D/Activity( 7427): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/OpenGLRenderer( 7427): Render dirty regions requested: true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
,I/SurfaceFlinger(  252): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
I/OpenGLRenderer( 7427): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7427): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7427): Enabling debug mode 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Adreno-ES20( 7427): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7427): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  890): Displayed com.test.thalitest/.MainActivity: +720ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/art     (  890): Explicit concurrent mark sweep GC freed 43723(2MB) AllocSpace objects, 18(2023KB) LOS objects, 29% free, 37MB/53MB, paused 1.422ms total 117.894ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  252): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
,I/SurfaceFlinger(  252): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{237f1567 u0 com.test.thalitest/.MainActivity t12} time:99053
D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline( 7427): Timeline: Activity_idle id: android.os.BinderProxy@3e236864 time:99054
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/JsMessageQueue( 7427): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/PhoneStatusBar( 1170): Icon Only
I/SurfaceFlinger(  252): id=15 Removed Starting com.test.thalitest (6/8)
,I/SurfaceFlinger(  252): id=15 Removed Starting com.test.thalitest (-2/8)
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4987405110241113019&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/jxcore_app_log( 7427): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259382784
,D/JX-Cordova( 7427): jxcore cordova android initializing
,D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@10
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4987405110241113019&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4987405110241113019&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 68969, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  890): Killing 6564:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  890): failed to open /acct/uid_10075/pid_6564/cgroup.procs: No such file or directory
,D/PowerManagerService(  890): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  890): getFinalBrightness : 15 -> 15
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  890): lcd : 19 +
,D/lights  (  890): lcd : 19 -
,D/lights  (  890): lcd : 15 +
D/DisplayPowerController(  890): getFinalBrightness : 15 -> 15
,D/lights  (  890): lcd : 15 -
,D/DisplayPowerController(  890): getFinalBrightness : 15 -> 15
,E/SMD     (  287): DCD ON
,W/jxcore-log( 7427): Initializing JXcore engine
,W/jxcore-log( 7427): JXcore engine is ready
,W/jxcore-log( 7427): Starting JXcore engine
,E/auditd  ( 2044): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  890): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  890): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7485): MountEmulatedStorage()
E/Zygote  ( 7485): v2
I/libpersona( 7485): KNOX_SDCARD checking this for 1000
I/libpersona( 7485): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7485 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 13.791ms total 35.921ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 9.705ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 9.178ms
,D/TimaKeyStoreProvider( 7485): TimaSignature is unavailable
,D/ActivityThread( 7485): Added TimaKeyStore provider
,D/ResourcesManager( 7485): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7485):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7485):  SeDenialReceiver : File path = null
,I/ActivityManager(  890): Killing 6580:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/jxcore-log( 7427): Platform android
W/jxcore-log( 7427): 
W/jxcore-log( 7427): Process ARCH arm
W/jxcore-log( 7427): 
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6580/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,I/jxcore-log( 7427): JXcore Cordova bridge is ready!
I/jxcore-log( 7427): 
,W/jxcore-log( 7427): JXcore engine is started
,D/TaskPersister(  890): removeObsoleteFile: deleting file=11_task_thumbnail.png
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7427): Toggling radios to true
I/jxcore-log( 7427): 
,D/BluetoothAdapter( 7427): enable()
,D/BluetoothAdapter( 7427): enable(): BT is already enabled..!
,D/WifiService(  890): New client listening to asynchronous messages
,I/WifiManager( 7427): packageName : com.test.thalitest
,D/SecContentProvider(  890): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  890): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  890): mCursor = null
,D/WifiService(  890): setWifiEnabled: true pid=7427, uid=10367
E/WifiService(  890): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  890): Permission Denial: getCurrentUser() from pid=7427, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  890): Failed getting userId using ActivityManagerNative
W/WifiService(  890): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7427, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  890): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  890): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  890): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  890): name = wifi_on
I/WifiService(  890): disconnect: pid=7427, uid=10367
,I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7427): Radios toggled
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Received device characteristics:
I/jxcore-log( 7427): Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7427): Bluetooth name: Thali Test (Galaxy S5)
I/jxcore-log( 7427): Device name: samsung-SM-G900F
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Perf Test app loaded loaded
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): check test folder
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): found test : ./testFindPeers.js
I/jxcore-log( 7427): 
,I/wpa_supplicant( 1271): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1271): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1271): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1271): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1271): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1271): Disconnected - do not scan
I/wpa_supplicant( 1271): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  890): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,I/jxcore-log( 7427): found test : ./testSendData.js
I/jxcore-log( 7427): 
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  281): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1669): Read error: ssl=0xaf33c600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1669): SSL shutdown failed: ssl=0xaf33c600: I/O error during system call, Broken pipe
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-3ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
D/ConnectivityService(  890): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  890): calling update connectivity
,D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine(  890): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): ignoring duplicate network state non-change
,D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  890): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1271): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1271): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1271): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1271): First Scan Start
,I/wpa_supplicant( 1271): Scan requested (ret=0) - scan timeout 30 seconds
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  890): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 1302): Starting #6
,I/Hs20UtilService( 1302): Message received 5007
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  890): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  890): calling update connectivity
D/EntConnectivity(  890): Not allowed due to - mEnabled false
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
,D/CommandListener(  281): Clearing all IP addresses on wlan0
,D/ConnectivityService(  890): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/CSLegacyTypeTracker(  890): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  890): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1460): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - currTime: 1452155878594
D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
I/Choreographer( 7427): Skipped 77 frames!  The application may be doing too much work on its main thread.
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  890): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/SmartBondingService(  890): getSBEnabled() enabled =false
V/NetworkStats(  890): updateIfacesLocked()
V/NetworkStats(  890): performPollLocked(flags=0x1)
,D/WifiNetworkAgent(  890): NetworkAgent: NetworkAgent channel lost
,D/NetworkStatsFactory(  890): UpdateStatsForKnox
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
,V/NetworkStats(  890): performPollLocked() took 7ms
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,I/chromium( 7427): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7427): 
,I/chromium( 7427): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/Hs20UtilService( 1302): Starting #7
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,I/chromium( 7427): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  890): updateDataUsageMap
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  890): MasterInitialState.processMessage what=3
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  890): CLoinfo wifi false
,D/accuweather( 2235): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
W/SLocation(  890): No Active Data Connection
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,I/DBG_DM  ( 3800): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5427): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 6784): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6784): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6784): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SystemBroadcastReceiver( 7167): [#DCM#] [DCM_Performance] onReceive completed in time  8705 microsec. 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): noConnectivity : true
,I/DBG_DM  ( 3800): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/SystemBroadcastReceiver( 7167): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7167): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7167): [#DCM#] setIsConnectedForExtractors 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7564): MountEmulatedStorage()
E/Zygote  ( 7564): v2
I/libpersona( 7564): KNOX_SDCARD checking this for 10002
I/libpersona( 7564): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7564 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7564): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7564): TimaSignature is unavailable
,D/ActivityThread( 7564): Added TimaKeyStore provider
,D/ResourcesManager( 7564): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,E/SMD     (  287): DCD ON
,I/ActivityManager(  890): Killing 6624:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7591): MountEmulatedStorage()
E/Zygote  ( 7591): v2
I/libpersona( 7591): KNOX_SDCARD checking this for 1000
I/libpersona( 7591): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7591 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7591): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7591): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7591): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Watchdog(  890): !@Sync 3
,D/TimaKeyStoreProvider( 7591): TimaSignature is unavailable
,D/ActivityThread( 7591): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6624/cgroup.procs: No such file or directory
,D/ResourcesManager( 7591): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7591): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7591): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7591): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7591): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7591): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7591): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/wpa_supplicant( 1271): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 1271): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1271): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1271): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  890): [1,452,155,879,597 ms] noteScanEnd no scan source
,E/WifiStateMachine(  890): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@10a8f9e2 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  890): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  890): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info0x
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7615): MountEmulatedStorage()
,E/Zygote  ( 7615): v2
I/libpersona( 7615): KNOX_SDCARD checking this for 10011
I/libpersona( 7615): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7615 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7615): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7615): TimaSignature is unavailable
,D/ActivityThread( 7615): Added TimaKeyStore provider
,I/wpa_supplicant( 1271): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,I/wpa_supplicant( 1271): Associated with C0.AA.48
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager( 7615): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1271): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/ActivityManager(  890): Killing 6743:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/FOTA_Client( 7615): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7615): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/wpa_supplicant( 1271): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1271): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1271): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1271): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1271): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1271): Blacklist: Clear (temp) 
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): Network connection established
,D/WifiNative-HAL(  890): callSECApiVoid - ID [50]
,E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  890): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  890): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  890): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  890): Got NetworkAgent Messenger
D/ConnectivityService(  890): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): NetworkAgent connected
,E/WifiStateMachine(  890): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  890): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  890): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/FOTA_Client( 7615): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/CommandListener(  281): Setting iface cfg
,E/WifiStateMachine(  890): Start Dhcp Watchdog 2
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/FOTA_Client( 7615): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/FOTA_Client( 7615): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
E/WifiStateMachine(  890): calculateWifiScore() report new score 60
,I/WifiStateMachine(  890): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  890): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,D/ConnectivityService(  890): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/Zygote  ( 7631): MountEmulatedStorage()
E/Zygote  ( 7631): v2
I/libpersona( 7631): KNOX_SDCARD checking this for 10019
I/libpersona( 7631): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7631 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6768:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SELinux ( 7631): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7631): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  890): failed to open /acct/uid_10015/pid_6743/cgroup.procs: No such file or directory
E/SELinux ( 7631): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_10016/pid_6768/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7631): TimaSignature is unavailable
,D/ActivityThread( 7631): Added TimaKeyStore provider
,D/ResourcesManager( 7631): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7631): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7631): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452155879928
,I/KLMS-2.4.503: ( 7631): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  890): do suspend false
,I/KLMS-2.4.503: ( 7631): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7631): StateImplV2(): networkChangeListener().END
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,I/ActivityManager(  890): Killing 6536:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7646): MountEmulatedStorage()
,E/Zygote  ( 7646): v2
I/libpersona( 7646): KNOX_SDCARD checking this for 10037
I/libpersona( 7646): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7646 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7646): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7646): TimaSignature is unavailable
,D/ActivityThread( 7646): Added TimaKeyStore provider
,D/ResourcesManager( 7646): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,V/AlarmManager(  890): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,W/libprocessgroup(  890): failed to open /acct/uid_10034/pid_6536/cgroup.procs: No such file or directory
,I/SO_AGENT( 7646): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SPPClientService( 5102): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6822): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6822): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6822): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6822): [SLFUCHKMGR] constructor called
,E/SPPClientService( 5102): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6822): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6822): [OR] == isSIMCardReady false ==
,I/SA      ( 6822): [SCU] == networkStateCheck == false
I/SA      ( 6822): [OR] onReceive END
,I/ActivityManager(  890): Killing 4614:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7669): MountEmulatedStorage()
,E/Zygote  ( 7669): v2
I/libpersona( 7669): KNOX_SDCARD checking this for 10071
I/libpersona( 7669): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7669 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7669): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7669): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7669): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 7677): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7677): version 5.5.6 starting
,E/dhcpcd  ( 7677): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider( 7669): TimaSignature is unavailable
,D/ActivityThread( 7669): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10035/pid_4614/cgroup.procs: No such file or directory
,D/ResourcesManager( 7669): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7669): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7669): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7669): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7677): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7677): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7677): bssid match
,I/dhcpcd  ( 7677): wlan0: rebinding lease of 192.168.1.135
,D/comsamsunglog( 7669): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7669): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7669): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7669): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7669): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7669): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
D/comsamsunglog( 7669): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7669): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  890): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10071
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7669): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7669): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
D/accuweather( 7669): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7669): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7669): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7669): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7669): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7669): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7669): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7669): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7693): MountEmulatedStorage()
E/Zygote  ( 7693): v2
I/libpersona( 7693): KNOX_SDCARD checking this for 1000
I/libpersona( 7693): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6098:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_10042/pid_6098/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7693): TimaSignature is unavailable
,D/ActivityThread( 7693): Added TimaKeyStore provider
,D/ResourcesManager( 7693): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7693): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7693): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7693): premStatus:2
,I/KnoxUsageLogPro( 7693): isEulaShown : false
,I/KnoxUsageLogPro( 7693): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7708): MountEmulatedStorage()
E/Zygote  ( 7708): v2
I/libpersona( 7708): KNOX_SDCARD checking this for 10088
I/libpersona( 7708): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7708 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5752:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7708): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/CountryDetector(  890): No listener is left
,I/SELinux ( 7708): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7708): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7708): TimaSignature is unavailable
,D/ActivityThread( 7708): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10050/pid_5752/cgroup.procs: No such file or directory
,D/ResourcesManager( 7708): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  890): Killing 6843:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5557): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5557): getCountryCode(): countryCode = DE
,D/Headlines( 5557): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5557): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5557): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5557): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5557): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5557): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5557): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7727): MountEmulatedStorage()
E/Zygote  ( 7727): v2
I/libpersona( 7727): KNOX_SDCARD checking this for 10128
I/libpersona( 7727): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7727 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7727): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_10051/pid_6843/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7727): TimaSignature is unavailable
,D/ActivityThread( 7727): Added TimaKeyStore provider
,D/ResourcesManager( 7727): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  251): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  251): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7727): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  251): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  251): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7727): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  251): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  251): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7727): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  251): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  251): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7727): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7727): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7727): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7727): Loading: webviewchromium
,I/LibraryLoader( 7727): Time to load native libraries: 4 ms (timestamps 5233-5237)
,I/LibraryLoader( 7727): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7727): Binding Chromium to main looper Looper (main, tid 1) {2ebf1663}
,I/LibraryLoader( 7727): Expected native library version number "",actual native library version number ""
,I/chromium( 7727): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7727): Initializing chromium process, renderers=0
,W/art     ( 7727): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7727): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7727): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7727): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7727): Requires BLUETOOTH permission
,I/Adreno-EGL( 7727): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7727): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7727): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7727): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7727): Remote Branch: 
I/Adreno-EGL( 7727): Local Patches: 
I/Adreno-EGL( 7727): Reconstruct Branch: 
,I/NSApplication( 7727): Starting up...
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7782): MountEmulatedStorage()
E/Zygote  ( 7782): v2
I/libpersona( 7782): KNOX_SDCARD checking this for 10138
I/libpersona( 7782): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7782 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6860:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7782): TimaSignature is unavailable
,D/ActivityThread( 7782): Added TimaKeyStore provider
,D/ResourcesManager( 7782): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7782): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_10058/pid_6860/cgroup.procs: No such file or directory
W/ResourcesManager( 7782): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7782): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7782): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 7782): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7782): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7807 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 7807): MountEmulatedStorage()
,E/Zygote  ( 7807): v2
,I/libpersona( 7807): KNOX_SDCARD checking this for 10163
I/ActivityManager(  890): Killing 6229:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/libpersona( 7807): KNOX_SDCARD not a persona
,I/art     (  315): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 285us total 18.357ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 263us total 8.632ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 263us total 7.798ms
,I/SELinux ( 7807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7807): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6229/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7807): TimaSignature is unavailable
,D/ActivityThread( 7807): Added TimaKeyStore provider
,D/ResourcesManager( 7807): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7807): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7807): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7807): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/Zygote  ( 7835): MountEmulatedStorage()
I/libpersona( 7835): KNOX_SDCARD checking this for 10078
E/Zygote  ( 7835): v2
I/libpersona( 7835): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7835 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,I/SELinux ( 7835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7835): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 7835): TimaSignature is unavailable
,D/ActivityThread( 7835): Added TimaKeyStore provider
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  890): Killing 6880:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7485): StateMachine : Current State = 1
,D/SecurityLogAgent( 7485): StateMachine : Changed Current State = 1
,I/ActivityManager(  890): Killing 6943:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/ResourcesManager( 7835): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/com.peel.receiver.ConnectivityActionReceiver( 5662): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
,D/com.peel.receiver.ConnectivityActionReceiver( 5662): NO active network... no services...
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): last run: 1452155793897 -- System.currentTimeMillis()-last_run: 87612
D/com.peel.receiver.ConnectivityActionReceiver( 5662): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): ... skip last_72_check
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7835): onCreate
,D/BadgeProvider( 7835): DatabaseHelper
,E/Zygote  ( 7851): MountEmulatedStorage()
I/libpersona( 7851): KNOX_SDCARD checking this for 10178
E/Zygote  ( 7851): v2
I/libpersona( 7851): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7851 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
I/SELinux ( 7851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
I/SELinux ( 7851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
E/SELinux ( 7851): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/BadgeProvider( 7835): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7851): TimaSignature is unavailable
,D/ActivityThread( 7851): Added TimaKeyStore provider
,D/BadgeProvider( 7835): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7835): sendNotify, [notify] : null
D/BadgeProvider( 7835): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7835): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7835): update, [UpdateCount] : 1
,D/Launcher.Model( 1480): reloadBadges entered.
,D/ResourcesManager( 7851): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7807): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,W/libprocessgroup(  890): failed to open /acct/uid_10098/pid_6880/cgroup.procs: No such file or directory
,W/libprocessgroup(  890): failed to open /acct/uid_10033/pid_6943/cgroup.procs: No such file or directory
,I/ActivityManager(  890): Killing 6909:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,I/dhcpcd  ( 7677): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,I/iu.Environment( 2392): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2392): num queued entries: 0
,I/iu.UploadsManager( 2392): num updated entries: 0
,I/iu.SyncManager( 2392): NEXT; no task
,I/dhcpcd  ( 7677): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup(  890): failed to open /acct/uid_10099/pid_6909/cgroup.procs: No such file or directory
,I/Hs20UtilService( 1302): Starting #8
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,W/ActivityManager(  890): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  890): WifiStateMachine DHCP successful
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/WifiStateMachine(  890): Not connected state, yet.
E/WifiStateMachine(  890): VerifyingLinkState enter
,D/WifiStateMachine(  890): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
,D/WifiStateMachine(  890): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  890): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  890): callSECApiInt - ID [210]
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  890): Adding iface wlan0 to network 503
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  890): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  890): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  890): Now, connected state.
E/WifiStateMachine(  890): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  890): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  890): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,D/ConnectivityService(  890): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  890): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  890): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  890): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  890): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  890): updateSourceRoutes : add src route for:192.168.1.135
V/        (  281): QcRouteController
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): ConnectedState Enter  mScreenOn=true scanperiod=20000
I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  890): mBoosterFLAG : 0
I/WifiTrafficPoller(  890): current booster mode : FullMode
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiNative-HAL(  890): callSECApiVoid - ID [212]
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
,V/        (  281): QcRouteController
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,I/Hs20UtilService( 1302): Starting #9
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,V/        (  281): QcRouteController
,D/PowerManagerService(  890): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  890): Nap time (uid 1000)...
I/PowerManagerService(  890): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  890): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService(  890): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  890): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  890): handleSandman : startDream()
D/InputManager-JNI(  890): setDeviceInteractive: 0
,E/PowerManagerService(  890): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  890): Sleeping (uid 1000)...
D/PowerManagerService(  890): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  890): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  890): [input device light] handleInputDeviceLightOff
,I/Hs20UtilService( 1302): Starting #10
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event2/device/enabled: 0
I/SurfaceFlinger(  252): id=17 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,I/Hs20UtilService( 1302): Message received 5007
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,V/        (  281): QcRouteController
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  890): 	.unregisterCallback : 1, client=
D/SContextService(  890): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@104dc282, Service = Auto Rotation, used = 1
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  890): stop(ContextProvider.java:149)
,V/CAE     (  890): clear(AutoRotationRunner.java:182)
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/CAE     (  890): disable(AutoRotationRunner.java:171)
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  890): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  300): sendContextData: -78, 7, 0, 0
,V/        (  281): QcRouteController
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/CAE     (  890): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  890): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1302): Starting #11
,I/Hs20UtilService( 1302): Message received 5007
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  890): callSECApi what=220
,D/WifiStateMachine(  890): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  281): QcRouteController
,V/        (  281): QcRouteController
,D/CAE     (  890): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  890): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  890): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  890): removeSContextService() : service = Auto Rotation
D/SContextService(  890): ===== SContext Service List =====
D/SContextManager(  890):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@19eff56b, service=Auto Rotation
,D/KeyguardViewMediator( 1170): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1170): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1170): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1170): notifyScreenOffLocked
,V/        (  281): QcRouteController
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): timeout : 5000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SQLiteSecureOpenHelper( 3563): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3563): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 1170): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1170): handleNotifyScreenOff
,I/SurfaceFlinger(  252): id=18 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  890): Setting Dns servers for network 503 to [/192.168.1.1]
D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 14
,D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890): ignoring duplicate network state non-change
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): ignoring duplicate network state non-change
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): currentScore = 0, newScore = 60
D/ConnectivityService(  890):    accepting network in place of null
D/ConnectivityService(  890): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1460): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
E/CSLegacyTypeTracker(  890): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  890): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  890): turn on LED for fully charged
D/SensorManager(  890): unregisterListener ::   
D/lights  (  890): led_pattern : 5 +
D/DisplayPowerController(  890): ColorFade: onAnimationStart
D/DisplayPowerController(  890): getFinalBrightness : 28 -> 0
D/lights  (  890): led_pattern : 5 -
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService(  890): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890
D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  890): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EntConnectivity(  890): Not allowed due to - mEnabled false
D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/lights  (  890): lcd : 11 +
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): updateIfacesLocked()
V/NetworkStats(  890): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  890): UpdateStatsForKnox
D/ConnectivityService(  890): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
V/NetworkStats(  890): performPollLocked() took 9ms
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/lights  (  890): lcd : 11 -
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/lights  (  890): lcd : 2 +
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/CAE     (  890): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  890): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -76, 13, -46, 0
D/DisplayPowerController(  890): getFinalBrightness : 28 -> 0
D/Sensorhubs(  300): sendContextData: -76, 13, -46, 0
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 8, 38, 2,
D/SensorHubManager(  890): SendSensorHubData: send data = -63, 14, 8, 38, 2
D/Sensorhubs(  300): sendContextData: -63, 14, 8, 38, 2
D/lights  (  890): lcd : 2 -
D/lights  (  890): lcd : 0 +
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  890):  handler : SCREEN_OFF end 
D/lights  (  890): lcd : 0 -
D/NotificationService(  890): ACTION_SCREEN_OFF
D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
D/WifiStateMachine(  890): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 14
E/WifiStateMachine(  890): handleScreenStateChanged Exit: false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/WifiStateMachine(  890): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  890): do suspend true
D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SensorManager(  890): unregisterListener ::   
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: enter: screen_state=off
V/voice   (  294): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  294): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  294): adev_set_parameters: exit
E/SMD     (  287): DCD ON
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SecExternalDisplayIntents_Java(  890): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  890): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  890): Bridge Server is not available
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1170): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1170): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PersonaManagerService(  890): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  890): MSG_ACTION_SCREEN_OFF called
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/NfcService( 1450): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1170):      ACTION_SCREEN_OFF is finished!!!! 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/StatusBar( 1170): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1170): dismissHelpPopup 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/accuweather( 2235): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2235): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,D/accuweather( 2235): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DisplayPowerState(  890): !@ ColorFade entry
,D/DisplayPowerController(  890): ColorFade: onAnimationEnd
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  890): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/SensorManager(  890): unregisterListener ::   
D/LockPatternUtilsCache( 1170): value : false
E/Sensors (  890): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SensorManager(  890): unregisterListener ::   
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  890): SIOP:: AP = 390, PST = 415, CUR = 300
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SystemBroadcastReceiver( 7167): [#DCM#] [DCM_Performance] onReceive completed in time  272 microsec. 
,I/SystemBroadcastReceiver( 7167): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7167): [#DCM#] onReceive action = EVENT_SCREEN_OFF
D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Broadcasts
,I/DCMController( 7167): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  890): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
D/SurfaceFlinger(  252): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  252): hwc_blank: Blanking display: 0
,V/ActivityManager(  890): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  276): 
,I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2235): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Tethering(  890): MasterInitialState.processMessage what=3
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  890): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  890): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): CLocinfo wifi true 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qdhwcomposer(  252): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  252): hwc_blank: Done blanking display: 0
,D/PowerManagerService(  890): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceControl(  890): Excessive delay in setPowerMode(): 280ms
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/MISC PowerHAL(  890): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  890): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL(  890): Got set_interactive hint
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2118): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2118): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  890): [PWL] Off : 0s ago
I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=890, ws=null) (elapsedTime=4175)
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'SyncLoopWakeLock' (uid=1000, pid=890, ws=null) (elapsedTime=21)
I/PowerManagerService(  890): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  890): [PWL]     mDisplayReady : false
D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Display
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7167): [#DCM#] [DCM_Performance] onReceive completed in time  92 microsec. 
I/SystemBroadcastReceiver( 7167): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7167): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7167): [#DCM#] setIsConnectedForExtractors 
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3800): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3800): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor( 5427): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7167): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,I/FrameworkService( 7167): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7167): [#DCM#] onCreate FrameworkService end 
I/DCMConfig( 7167): [#DCM#] getSuccessState = true
,I/PCWCLIENTTRACE_PushUtil( 6784): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6784): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6784): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/FrameworkService( 7167): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7167): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemUtils( 7167): [#DCM#] LM: false,AM:661995520
,I/DCMThreadPoolExecutor( 7167): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7167): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@38a95601 is submitted
I/FrameworkService( 7167): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 33734 mirosec. 
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,I/DIAGMON_AGENT( 7591): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7591): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/art     (  890): Explicit concurrent mark sweep GC freed 79571(4MB) AllocSpace objects, 6(161KB) LOS objects, 29% free, 38MB/54MB, paused 1.794ms total 124.950ms
,I/FOTA_Client( 7615): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7615): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7615): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7615): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7615): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/KLMS-2.4.503: ( 7631): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7631): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452155883072
,I/KLMS-2.4.503: ( 7631): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7631): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7631): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7631): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7631): StateImplV2(): networkChangeListener().END
,I/SO_AGENT( 7646): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  890): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7427): BLE is supported
I/jxcore-log( 7427): 
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5102): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6822): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6822): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6822): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/SA      ( 6822): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6822): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6822): [SCU] == networkStateCheck == true
,I/SA      ( 6822): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6822): isChinaCountryCode : false
,I/SA      ( 6822): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 6822): [OR] == networkStateCheck true ==
,I/SA      ( 6822): [OR] GetMyCountryZoneTask
,I/SA      ( 6822): [OR] onReceive END
,I/SA      ( 6822): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6822): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/accuweather( 7669): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7669): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6822): [SSP] query invoked
,I/KnoxUsageLogPro( 7693): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7693): premStatus:2
,I/KnoxUsageLogPro( 7693): isEulaShown : false
,I/KnoxUsageLogPro( 7693): KnoxUsageReceiver onReceive : not Processible, just return
,D/Headlines( 5557): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5557): getCountryCode(): countryCode = DE
,D/Headlines( 5557): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5557): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5557): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5557): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5557): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5557): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5557): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7782): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7782): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7782): PeriphStartReceiver.onReceive - no need to start
,I/SA      ( 6822): [TPMU] GetMccFromDB : null
I/SA      ( 6822): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6822): [TPM] isNoProxy(default) : true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7485): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7485): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7485): StateMachine : Current State = 1
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 7485): StateMachine : Changed Current State = 1
,E/File    ( 6822): fail readDirectory() errno=2
,D/com.peel.receiver.ConnectivityActionReceiver( 5662): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): last run: 1452155793897 -- System.currentTimeMillis()-last_run: 89767
D/com.peel.receiver.ConnectivityActionReceiver( 5662): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5662): ... skip last_72_check
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 2392): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2392): num queued entries: 0
,I/iu.UploadsManager( 2392): num updated entries: 0
,I/iu.SyncManager( 2392): NEXT; no task
,D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2392): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7136): notifyNetworkActivated
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  890): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  890): identical MTU - not setting
D/ConnectivityService(  890): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  890): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
V/        (  281): QcRouteController
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/        (  281): QcRouteController
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,W/ContextImpl( 7136): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/NetworkManagementService(  890): route cmd failed: 
W/NetworkManagementService(  890): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  890): '
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  890): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  890): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  890): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524295
,W/ActivityManager(  890): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,W/Kids    ( 2392): [AccountUtils] Account not ready
W/Kids    ( 2392): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2392): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2392): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2392): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2392): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2392): 	at java.lang.Thread.run(Thread.java:818)
,D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1669): Connected
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1669): Message class com.google.f.a.a.p
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7136): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7136): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7136): exit::IDLE
,D/InitializeManagerStateMachine( 7136): entry::NETWORK_CHECK
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7136): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7136): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7136): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7136): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7136): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7136): entry::SUCCESS
D/hcjo    ( 7136): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7136): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7136): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7136): exit::SUCCESS
D/InitializeManagerStateMachine( 7136): entry::IDLE
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6822): [RC New] Execute method=[GET] start
,I/SA      ( 6822): [RC New] Security=[true]
,I/System.out( 6822): Thread-1110(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6822): Thread-1110(ApacheHTTPLog):isShipBuild true
,I/System.out( 6822): Thread-1110(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  287): DCD ON
,I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  890): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger(  252): id=18 Removed Toast (8/9)
,I/SurfaceFlinger(  252): id=18 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  890): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 890) eventTime = 110037
,D/PowerManagerService(  890): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890 (0x0)
,D/PowerManagerService(  890): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=890, ws=WorkSource{10059}) (elapsedTime=3465)
,I/SA      ( 6822): [RC New] [v2liruge] api execute + 840
,I/SA      ( 6822): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6822): AsyncTask #1 calls detatch()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SA      ( 6822): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6822): [OCP] update openData : PL
,I/SA      ( 6822): [TPMU] getNetworkMcc : 
,I/SA      ( 6822): [SCU] saveMccToPreferece Start
,I/SA      ( 6822): [SCU] RegionMCC : 260
I/SA      ( 6822): [SSP] query invoked
,I/SA      ( 6822): [TPMU] GetMccFromDB : null
,I/SA      ( 6822): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6822): [SCU] saveMccToPreferece End
,I/SA      ( 6822): [RC New] executeRequest [v2liruge] end. 1024
,I/SA      ( 6822): [RC New] Execute end
,I/SA      ( 6822): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6822): [OR] GetMyCountryZoneTask Success
,I/GAV4    ( 7727): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardViewMediator( 1170): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/KeyguardViewMediator( 1170): doKeyguard: not showing because lockscreen is off
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  890): [PWL] Off : 5s ago
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): mConnectivityHandler : connected
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6784): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6784): ================================================
,I/CSTORAGE( 6784):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6784): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6784): [GetString-S]
,E/art     ( 6784): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6784): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6784): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6784): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6784): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6784): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6784): [ensureRegistration] - No Samsung account
,E/SMD     (  287): DCD ON
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/FactoryTest( 6504): Not factory mode,
,D/FactoryTest( 6504): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6504): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6504): still no open session command from host, so toast
,W/ContextImpl( 6504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6504): Timeline: Activity_launch_request id:com.android.settings time:115886
,E/PersonaManagerService(  890): inState():  stateMachine is null !!
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  890): mDVFSHelper.acquire()
,V/ActivityManager(  890): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6504): started activity for popup
,I/SQLiteSecureOpenHelper( 3563): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3563): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6504): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6504): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6504): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6504): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6504): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6504): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6504): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6504): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6504): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  890): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@c832c63 attribute=android.view.inputmethod.EditorInfo@2f24060, token = android.os.BinderProxy@809c4d3
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,W/ActivityManager(  890): Activity pause timeout for ActivityRecord{132b88f4 u0 com.android.settings/.SettingsReceiverActivity t13 f}
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
,V/BitmapFactory( 6504): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 7427): Timeline: Activity_idle id: android.os.BinderProxy@3e236864 time:116550
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/SettingsReceiverActivity( 6504): dev.kiessupport is : TRUE
,D/Activity( 6504): performCreate Call secproduct feature valuefalse
D/Activity( 6504): performCreate Call debug elastic valuetrue
,I/dhcpcd  ( 7677): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7677): wlan0: no IPv6 Routers available
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 340, PST = 403, CUR = 300
,D/X       (  890): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/TranscodeReceiver( 7228): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/ContentApp( 1225):  LEVEL : -1
,D/TranscodeReceiver( 7228):  SIOP_LEVEL: -1
,I/SystemBroadcastReceiver( 7167): [#DCM#] [DCM_Performance] onReceive completed in time  54413 microsec. 
,I/SystemBroadcastReceiver( 7167): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7167): [#DCM#] onReceive action = EVENT_SIOP
,V/AlarmManager(  890): waitForAlarm result :4
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 3.
,D/PreloadUpdateManagerStateMachine( 7136): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7136): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7136): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7136): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7136): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7136): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7136): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7136): entry::IDLE
,E/SMD     (  287): DCD ON
,W/ActivityManager(  890): mDVFSHelper.release()
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  890): [PWL] Off : 15s ago
,I/ActivityManager(  890): Waited long enough for: ServiceRecord{3f9ece8a u0 com.samsung.dcm/.framework.FrameworkService}
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 330, PST = 389, CUR = 300
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 4
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 373, CUR = 300
,I/PowerManagerService(  890): [PWL] Off : 30s ago
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 359, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1669): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at dsf.a(PG:807)
E/HttpOperation( 6639): 	at fhk.a(PG:1126)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 8 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 10 more
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at ieo.a(PG:43)
E/HttpOperation( 6639): 	at iep.a(PG:93)
E/HttpOperation( 6639): 	at fhn.a(PG:59)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,E/ExperimentLoader( 6639): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): 	at kfv.a(PG:65)
E/ExperimentLoader( 6639): 	at kff.u(PG:385)
E/ExperimentLoader( 6639): 	at kfb.a(PG:29)
E/ExperimentLoader( 6639): 	at kff.l(PG:132)
E/ExperimentLoader( 6639): 	at ieo.a(PG:43)
E/ExperimentLoader( 6639): 	at iep.a(PG:93)
E/ExperimentLoader( 6639): 	at fhn.a(PG:59)
E/ExperimentLoader( 6639): 	at lex.a(PG:85)
E/ExperimentLoader( 6639): 	at lex.b(PG:132)
E/ExperimentLoader( 6639): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6639): 	at fhk.a(PG:908)
E/ExperimentLoader( 6639): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6639): 	at ihi.a(PG:22)
E/ExperimentLoader( 6639): 	at kft.a(PG:91)
E/ExperimentLoader( 6639): 	at kfv.a(PG:62)
E/ExperimentLoader( 6639): 	... 12 more
E/ExperimentLoader( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6639): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6639): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6639): 	at ihi.a(PG:19)
E/ExperimentLoader( 6639): 	... 14 more
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [getaccountstatus] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at ixd.a(PG:248)
E/HttpOperation( 6639): 	at ixd.b(PG:206)
E/HttpOperation( 6639): 	at ixd.a(PG:175)
E/HttpOperation( 6639): 	at fig.a(PG:78)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,E/EsSyncAdapterService( 6639): Sync failure
E/EsSyncAdapterService( 6639): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6639): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6639): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6639): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6639): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6639): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6639): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6639): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6639): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6639): 	... 10 more
E/EsSyncAdapterService( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6639): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6639): 	... 12 more
E/EsSyncAdapterService( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6639): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6639): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6639): 	... 14 more
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 124553, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 350, CUR = 300
,I/PowerManagerService(  890): [PWL] Off : 50s ago
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 5
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 340, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 330, CUR = 300
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1669): Vacuum at: now=1452155955210 tag=VacuumService
,I/GoogleURLConnFactory( 1669): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Uploader( 1669): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1669): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1669): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1669): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1669): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1669): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1669): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1669): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1669): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1669): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/System.out( 1669): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1669): (HTTPLog)-Static: isShipBuild true
I/System.out( 1669): (HTTPLog)-Thread-197-463055562: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1669): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1669, getuid(): 10012
,I/qtaguid ( 1669): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1669, getuid(): 10012
,I/art     (  890): Explicit concurrent mark sweep GC freed 56010(3MB) AllocSpace objects, 30(805KB) LOS objects, 29% free, 38MB/54MB, paused 2.142ms total 173.773ms
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1669): No account for auth token provided
,I/qtaguid ( 1669): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1669, getuid(): 10012
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6669): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6669): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6669): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1669): No account for auth token provided
,I/qtaguid ( 1669): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1669, getuid(): 10012
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1669): No account for auth token provided
,I/qtaguid ( 1669): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1669, getuid(): 10012
,W/Uploader( 1669):  no longer exists, so no auth token.
,I/qtaguid ( 1669): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1669, getuid(): 10012
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/PowerManagerService(  890): [PWL] Off : 75s ago
,I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=890, ws=WorkSource{10082}) (elapsedTime=214)
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-154157025423349687&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-154157025423349687&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/art     ( 1669): Explicit concurrent mark sweep GC freed 62484(3MB) AllocSpace objects, 62(4MB) LOS objects, 40% free, 18MB/30MB, paused 780us total 55.725ms
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  287): DCD ON
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1669): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-154157025423349687&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-154157025423349687&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-154157025423349687&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 165657, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1669): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at dsf.a(PG:807)
E/HttpOperation( 6639): 	at fhk.a(PG:1126)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 8 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 10 more
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at ieo.a(PG:43)
E/HttpOperation( 6639): 	at iep.a(PG:93)
E/HttpOperation( 6639): 	at fhn.a(PG:59)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,E/ExperimentLoader( 6639): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): 	at kfv.a(PG:65)
E/ExperimentLoader( 6639): 	at kff.u(PG:385)
E/ExperimentLoader( 6639): 	at kfb.a(PG:29)
E/ExperimentLoader( 6639): 	at kff.l(PG:132)
E/ExperimentLoader( 6639): 	at ieo.a(PG:43)
E/ExperimentLoader( 6639): 	at iep.a(PG:93)
E/ExperimentLoader( 6639): 	at fhn.a(PG:59)
E/ExperimentLoader( 6639): 	at lex.a(PG:85)
E/ExperimentLoader( 6639): 	at lex.b(PG:132)
E/ExperimentLoader( 6639): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6639): 	at fhk.a(PG:908)
E/ExperimentLoader( 6639): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6639): 	at ihi.a(PG:22)
E/ExperimentLoader( 6639): 	at kft.a(PG:91)
E/ExperimentLoader( 6639): 	at kfv.a(PG:62)
E/ExperimentLoader( 6639): 	... 12 more
E/ExperimentLoader( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6639): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6639): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6639): 	at ihi.a(PG:19)
E/ExperimentLoader( 6639): 	... 14 more
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [getaccountstatus] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at ixd.a(PG:248)
E/HttpOperation( 6639): 	at ixd.b(PG:206)
E/HttpOperation( 6639): 	at ixd.a(PG:175)
E/HttpOperation( 6639): 	at fig.a(PG:78)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,E/EsSyncAdapterService( 6639): Sync failure
E/EsSyncAdapterService( 6639): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6639): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6639): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6639): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6639): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6639): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6639): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6639): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6639): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6639): 	... 10 more
E/EsSyncAdapterService( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6639): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6639): 	... 12 more
E/EsSyncAdapterService( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6639): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6639): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6639): 	... 14 more
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 182927, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 324, CUR = 300
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 6
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 320, CUR = 300
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 310, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  890): [PWL] Off : 105s ago
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 305, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 7
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 301, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 298, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2535398339453156862&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2535398339453156862&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2535398339453156862&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2535398339453156862&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2535398339453156862&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 218098, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  890): Explicit concurrent mark sweep GC freed 44616(2MB) AllocSpace objects, 30(1065KB) LOS objects, 29% free, 37MB/53MB, paused 1.869ms total 134.703ms
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,I/PowerManagerService(  890): [PWL] Off : 140s ago
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 296, CUR = 300
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 8
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  287): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at dsf.a(PG:807)
E/HttpOperation( 6639): 	at fhk.a(PG:1126)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 8 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 10 more
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at ieo.a(PG:43)
E/HttpOperation( 6639): 	at iep.a(PG:93)
E/HttpOperation( 6639): 	at fhn.a(PG:59)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,E/ExperimentLoader( 6639): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): 	at kfv.a(PG:65)
E/ExperimentLoader( 6639): 	at kff.u(PG:385)
E/ExperimentLoader( 6639): 	at kfb.a(PG:29)
E/ExperimentLoader( 6639): 	at kff.l(PG:132)
E/ExperimentLoader( 6639): 	at ieo.a(PG:43)
E/ExperimentLoader( 6639): 	at iep.a(PG:93)
E/ExperimentLoader( 6639): 	at fhn.a(PG:59)
E/ExperimentLoader( 6639): 	at lex.a(PG:85)
E/ExperimentLoader( 6639): 	at lex.b(PG:132)
E/ExperimentLoader( 6639): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6639): 	at fhk.a(PG:908)
E/ExperimentLoader( 6639): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6639): 	at ihi.a(PG:22)
E/ExperimentLoader( 6639): 	at kft.a(PG:91)
E/ExperimentLoader( 6639): 	at kfv.a(PG:62)
E/ExperimentLoader( 6639): 	... 12 more
E/ExperimentLoader( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6639): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6639): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6639): 	at ihi.a(PG:19)
E/ExperimentLoader( 6639): 	... 14 more
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6639): [getaccountstatus] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at ixd.a(PG:248)
E/HttpOperation( 6639): 	at ixd.b(PG:206)
E/HttpOperation( 6639): 	at ixd.a(PG:175)
E/HttpOperation( 6639): 	at fig.a(PG:78)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,E/EsSyncAdapterService( 6639): Sync failure
E/EsSyncAdapterService( 6639): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6639): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6639): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6639): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6639): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6639): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6639): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6639): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6639): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6639): 	... 10 more
E/EsSyncAdapterService( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6639): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6639): 	... 12 more
E/EsSyncAdapterService( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6639): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6639): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6639): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 247770, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 9
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 180s ago
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  287): DCD ON,
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  890): initializing...
,I/TLC_TIMA_PKM_initialize(  890): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  890): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  890): App is not loaded in QSEE
,D/QSEECOMAPI: (  890): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  890): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  890): Trustlet response is completed
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  890): [PWL] Off : 225s ago
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5719130451584027204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  890): waitForAlarm result :4
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 8237): MountEmulatedStorage()
,E/Zygote  ( 8237): v2
,I/libpersona( 8237): KNOX_SDCARD checking this for 10081
I/libpersona( 8237): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8237 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8237): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7427): Connected to the server!
I/jxcore-log( 7427): 
,D/TimaKeyStoreProvider( 8237): TimaSignature is unavailable
,D/ActivityThread( 8237): Added TimaKeyStore provider
,I/chromium( 7427): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ResourcesManager( 8237): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5719130451584027204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5719130451584027204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5719130451584027204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5719130451584027204&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7356): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 310697, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 11
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1669): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6669): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6669): Ignoring header User-Agent because its value was null.
,I/System.out( 6669): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6669): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6669): (HTTPLog)-Thread-1093-791268433: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 12
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 275s ago
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1669): Explicit concurrent mark sweep GC freed 41323(2MB) AllocSpace objects, 31(2MB) LOS objects, 40% free, 18MB/30MB, paused 652us total 51.052ms
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1669): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
E/HttpOperation( 6639): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at dsf.a(PG:807)
E/HttpOperation( 6639): 	at fhk.a(PG:1126)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 8 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 10 more
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 6639): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at ieo.a(PG:43)
E/HttpOperation( 6639): 	at iep.a(PG:93)
E/HttpOperation( 6639): 	at fhn.a(PG:59)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,D/PanelView( 1170): There is/are notification(s) 
,E/ExperimentLoader( 6639): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): 	at kfv.a(PG:65)
E/ExperimentLoader( 6639): 	at kff.u(PG:385)
E/ExperimentLoader( 6639): 	at kfb.a(PG:29)
E/ExperimentLoader( 6639): 	at kff.l(PG:132)
E/ExperimentLoader( 6639): 	at ieo.a(PG:43)
E/ExperimentLoader( 6639): 	at iep.a(PG:93)
E/ExperimentLoader( 6639): 	at fhn.a(PG:59)
E/ExperimentLoader( 6639): 	at lex.a(PG:85)
E/ExperimentLoader( 6639): 	at lex.b(PG:132)
E/ExperimentLoader( 6639): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6639): 	at fhk.a(PG:908)
E/ExperimentLoader( 6639): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6639): 	at ihi.a(PG:22)
E/ExperimentLoader( 6639): 	at kft.a(PG:91)
E/ExperimentLoader( 6639): 	at kfv.a(PG:62)
E/ExperimentLoader( 6639): 	... 12 more
E/ExperimentLoader( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6639): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6639): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6639): 	at ihi.a(PG:19)
E/ExperimentLoader( 6639): 	... 14 more
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
E/HttpOperation( 6639): [getaccountstatus] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at ixd.a(PG:248)
E/HttpOperation( 6639): 	at ixd.b(PG:206)
E/HttpOperation( 6639): 	at ixd.a(PG:175)
E/HttpOperation( 6639): 	at fig.a(PG:78)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
E/EsSyncAdapterService( 6639): Sync failure
E/EsSyncAdapterService( 6639): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6639): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6639): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6639): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6639): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6639): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6639): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6639): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6639): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6639): 	... 10 more
E/EsSyncAdapterService( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6639): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6639): 	... 12 more
E/EsSyncAdapterService( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6639): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6639): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6639): 	... 14 more
,D/PanelView( 1170): There is/are notification(s) 
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 395759, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2825): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2825): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     (  890): Explicit concurrent mark sweep GC freed 49124(2MB) AllocSpace objects, 59(1594KB) LOS objects, 29% free, 37MB/53MB, paused 2.545ms total 216.612ms
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 13
,V/AlarmManager(  890): waitForAlarm result :8
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 14
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 330s ago
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7427): --- start :testFindPeers.js---
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): testFindPeers created [object Object]
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): serverPort is 8876
I/jxcore-log( 7427): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): initialize: My bluetooth address is B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7427): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7427): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[152]}
,D/BluetoothSocket( 7427): bindListen(), new LocalSocket 
D/BluetoothSocket( 7427): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7427): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12be3265
D/BluetoothSocket( 7427): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): start: OK
I/io.jxcore.node.ConnectionHelper( 7427): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7427): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7427): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): start: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7427): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  890): InactiveState{ what=139292 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139292 }
D/WifiP2pService(  890): P2pEnabledState add service
,D/WifiP2pService(  890): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): start: Starting P2P device discovery...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  890): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 7427): start: OK
,I/jxcore-log( 7427): StartBroadcasting started ok
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7427): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 7427): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/chromium( 7427): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
D/WifiP2pManager( 7427): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,E/SMD     (  287): DCD ON
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/jxcore-log( 7427): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7427): 
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 15
,V/AlarmManager(  890): waitForAlarm result :8
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7356): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1669): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1599848454804400223&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
,W/ApiaryClient( 7356): Headers suppressed
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7356): null auth token
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
,I/art     ( 1170): Explicit concurrent mark sweep GC freed 71638(3MB) AllocSpace objects, 50(4MB) LOS objects, 30% free, 37MB/53MB, paused 2.030ms total 84.528ms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/qtaguid ( 7356): Untagging socket 34
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1599848454804400223&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1669): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1669): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1669): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1669): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1669): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7356): Authentication error
E/BooksAccountManager( 7356): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7356): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7356): null auth token
,I/PhoneStatusBar( 1170): Icon Only
,I/qtaguid ( 7356): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7356, getuid(): 10082
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/qtaguid ( 7356): Untagging socket 34
,W/ApiaryClient( 7356): Error response from books API: {
W/ApiaryClient( 7356):  "error": {
W/ApiaryClient( 7356):   "errors": [
W/ApiaryClient( 7356):    {
W/ApiaryClient( 7356):     "domain": "global",
W/ApiaryClient( 7356):     "reason": "required",
W/ApiaryClient( 7356):     "message": "Login Required",
W/ApiaryClient( 7356):     "locationType": "header",
W/ApiaryClient( 7356):     "location": "Authorization"
W/ApiaryClient( 7356):    }
W/ApiaryClient( 7356):   ],
W/ApiaryClient( 7356):   "code": 401,
W/ApiaryClient( 7356):   "message": "Login Required"
W/ApiaryClient( 7356):  }
W/ApiaryClient( 7356): }
,W/ApiaryClient( 7356): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1599848454804400223&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7356): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 7427): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 7427): 
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,E/SMD     (  287): DCD ON
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
E/BooksSync( 7356): Soft error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1599848454804400223&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7356): Sync error
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7356): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1599848454804400223&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7356): Headers suppressed
E/BooksSync( 7356): 
E/BooksSync( 7356): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7356): Finished books sync
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 465359, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
I/bootchecker(  319): bootchecker wake up!!
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 16
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 390s ago
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  287): DCD ON
,E/Watchdog(  890): !@Sync 17
,V/AlarmManager(  890): waitForAlarm result :8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  287): DCD ON
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,E/SMD     (  287): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  890): InactiveState{ what=139307 }
D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,I/jxcore-log( 7427): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 7427): 
,E/SMD     (  287): DCD ON
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
D/WifiP2pManager( 7427): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 7427): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7427): 
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log( 7427): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 7427): 
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7427): timeout now
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): weAreDoneNow
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): done, now sending data to server
I/jxcore-log( 7427): 
,E/Watchdog(  890): !@Sync 18
,E/SMD     (  287): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  287): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 455s ago
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
D/WifiP2pManager( 7427): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,I/jxcore-log( 7427): teardown
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): testFindPeers stopped
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): shutdown,
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@4648fe1, channel: 6, state: LISTENING
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@4648fe1, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12be3265, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bae0106mSocket: android.net.LocalSocket@2e0a73c7 impl:android.net.LocalSocketImpl@1ca41df4 fd:FileDescriptor[152]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@2e0a73c7 impl:android.net.LocalSocketImpl@1ca41df4 fd:FileDescriptor[152]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): stop: Stopping services
,D/WifiP2pService(  890): InactiveState{ what=139298 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139298 }
D/WifiP2pService(  890): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7427): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setState: NOT_STARTED
,I/jxcore-log( 7427): StopBroadcasting went ok
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): --- start :testSendData.js---
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 12
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): daya100000
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): check server
I/jxcore-log( 7427): 
I/jxcore-log( 7427): serverPort is 45946
I/jxcore-log( 7427): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): initialize: My bluetooth address is B0:C5:59:3F:75:69
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=139307 }
D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
D/WifiP2pService(  890): remove channel information from framework
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
D/WifiP2pService(  890): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7427): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 7427): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[153]}
,D/BluetoothSocket( 7427): bindListen(), new LocalSocket 
D/BluetoothSocket( 7427): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 7427): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29992792
D/BluetoothSocket( 7427): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): start: OK
I/io.jxcore.node.ConnectionHelper( 7427): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): start: Peer ID: B0:C5:59:3F:75:69, peer name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7427): verifyIdentityString: Identity string created: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7427): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): start: {"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7427): start: Identity string: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  890): InactiveState{ what=139292 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139292 }
D/WifiP2pService(  890): P2pEnabledState add service
,D/WifiP2pService(  890): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): start: Starting P2P device discovery...
D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  890): callSECApi what=74
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  890): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7427): start: OK
,I/jxcore-log( 7427): StartBroadcasting started ok
I/jxcore-log( 7427): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Waiting for incoming connections...
,I/jxcore-log( 7427): [ { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 7427):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 7427):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 7427):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 7427):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 7427):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 7427):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 7427):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 7427):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 7427):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 7427):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 7427):   { address: '08:EC:A9:50:75:41', tryCount: 0 } ]
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): startWithNextDevice
I/jxcore-log( 7427): 
I/jxcore-log( 7427): do fake peer & start
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
I/jxcore-log( 7427): 2016-01-07T08:45:45.772Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:45.772Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
I/jxcore-log( 7427): 2016-01-07T08:45:45.773Z SendDataConnector.js: do connect now
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): connect: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 7427): 2016-01-07T08:45:45.784Z SendDataTCPServer.js: TCP/IP server is bound to port: 45946
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7427): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7427): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7427): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7427): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 7427): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 1232)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/chromium( 7427): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7427): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothUtils( 7427): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
D/WifiP2pService(  890): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Failed to start the service discovery, got error code: 3
,D/bt_vendor( 3247): op for 7
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
,E/SMD     (  287): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value *
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): info:x10
,D/        ( 3247): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3247): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 3247): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,I/BluetoothBondStateMachine( 3247): Entering PendingCommandState State
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8439): MountEmulatedStorage()
,I/ActivityManager(  890): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.common.receiver.AutoLaunchReceiver: pid=8439 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,E/Zygote  ( 8439): v2
I/libpersona( 8439): KNOX_SDCARD checking this for 10099
,I/libpersona( 8439): KNOX_SDCARD not a persona
,I/SELinux ( 8439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8439): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8439): TimaSignature is unavailable
,D/ActivityThread( 8439): Added TimaKeyStore provider
,D/ResourcesManager( 8439): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 8439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/[CarMode]( 8439): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 8439): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 8439): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,D/btif_config_util( 3247): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3247): Failed to remove device: F8:95:C7:87:3C:51
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/HidService( 3247): getHidService(): returning com.android.bluetooth.hid.HidService@29f7321d
,D/SettingsProvider(  890): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
D/HidService( 3247): Saved priority F8:95:C7:87:3C:51 = -1
,D/SettingsProvider(  890): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/SettingsProvider(  890): ret = -1
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider(  890): name = bluetooth_headset_priority_F8:95:C7:87:3C:51
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
I/BluetoothBondStateMachine( 3247): StableState(): Entering Off State
,E/Zygote  ( 8470): MountEmulatedStorage()
,I/ActivityManager(  890): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=8470 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 8470): v2
I/libpersona( 8470): KNOX_SDCARD checking this for 10033
,I/libpersona( 8470): KNOX_SDCARD not a persona
,I/SELinux ( 8470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8470): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8470): TimaSignature is unavailable,
D/ActivityThread( 8470): Added TimaKeyStore provider
,D/ResourcesManager( 8470): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 8470): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/SMD     (  287): DCD ON
,I/System.out( 8470): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 8470): Inside WakeupProvider
,E/DatabaseUtils( 8470): Writing exception to parcel
E/DatabaseUtils( 8470): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 8470): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 8470): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 8470): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 8470): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 8470): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 8470): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 8470): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 8470): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 8470): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 8470): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 8439): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 8439): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 8439): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 8439): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 8439): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 8439): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 8439): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 8439): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 8439): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 8439): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 8439): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 8439): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 8439): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 8439): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 8439): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
,W/System.err( 8439): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 8439): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 8439): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 8439): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8439): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 8439): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8439): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8439): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8439): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8439): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8439): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 8470): Writing exception to parcel
E/DatabaseUtils( 8470): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 8470): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 8470): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 8470): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 8470): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 8470): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 8470): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 8470): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 8470): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 8470): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 8470): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 8439): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 8439): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 8439): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 8439): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 8439): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 8439): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 8439): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 8439): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 8439): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 8439): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 8439): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 8439): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 8439): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 8439): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 8439): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 8439): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 8439): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8439): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 8439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8439): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 8439): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 8439): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8439): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8439): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 8439): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 8439): [DLApplication]-Init Called!:false
E/[CarMode]( 8439): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 8439): DriveLinkServiceInterfaceImp-drivelink framework initialize start,
I/[CarModeFW]( 8439): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 8439): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 8439): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 8439): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 8439): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 8439): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 8439): ### android.app.ActivityThread$H::handleMessage(1483)
,I/[CarModeFW]( 8439): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 8439): ### android.os.Looper::loop(145)
I/[CarModeFW]( 8439): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 8439): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 8439): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 8439): ### com.android.internal.os.ZygoteInit::main(1194)
,I/MessageDataHandler( 8439): initialize
,D/[CarModeFW]( 8439): CDH-initiazlieCaches : before sync
,D/[CarModeFW]( 8439): CDH-initiazlieCaches : after sync
,I/VlingoApplication( 8470): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/[CarModeFW]( 8439): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 8439): CDH-ContactDataHandler initiazlieCaches time : 42
D/[CarModeFW]( 8439): CDH-initiazlieCaches : end sync
,D/[CarModeFW]( 8439): DrivingManager-initialize...
,I/SensorService(  890): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  890): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  890): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,I/VlingoAndroidCore( 8470): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,D/VlingoApplication( 8470): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 8470): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/bt_vendor( 3247): op for 7,
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/MediaPlayer( 8439): Need to enable context aware info
V/MediaPlayer-JNI( 8439): native_setup
V/MediaPlayer( 8439): constructor
,V/MediaPlayer( 8439): setListener
,E/MediaPlayer-JNI( 8439): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 8439): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 8439): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 8439): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1452156350787
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1452156350791
,D/[CarModeFW]( 8439): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1452156350793
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1452156350795
,D/[CarModeFW]( 8439): RecommendHandler-selection = type = '3'
,D/TP/SmsProvider( 1460): query,matched:2, calling pid = 8439
,D/TP/SmsProvider( 1460): match 2:Elapsed time : 1.192 ms
,D/[CarModeFW]( 8439): CDH-buildContactCacheWireFrame : cur len =0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1452156350816
,D/[CarMode]( 8439): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1452156350818
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
I/WifiStateMachine(  890): callSECApi what=74
D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MessageDataHandler( 8439):  getInboxList smsCursor : 42
,I/[CarMode]( 8439): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/TP/SmsProvider( 1460): query,matched:2, calling pid = 8439
,D/[CarModeFW]( 8439): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/SmsProvider( 1460): match 2:Elapsed time : 2.325 ms
,D/TP/MmsProvider( 1460): Query uri=content://mms/inbox, match=2, calling pid = 8439
,D/[CarModeFW]( 8439): RecommendHandler-selection = type = '3'
,E/[CarMode]( 8439): [DLApplication]-Init End!:true
,D/MessageDataHandler( 8439):  getInboxList mmsCursor : 27
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 79
,D/TP/MmsProvider( 1460): Query uri=content://mms, match=0, calling pid = 8439
,I/MessageDataHandler( 8439): getUnreadMessageCount :0
I/[CarModeFW]( 8439): -[snowdeer] Rec : Missed Call : 84
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 66
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/MessageDataHandler( 8439):  getInboxList mms,sms cursor join : 21
,I/SQLiteSecureOpenHelper( 6986): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 6986): getDatabaseLocked(b,b,pwd)...
,D/TP/MmsSmsProvider( 1460): query,matched:0, calling pid = 8439
V/TP/MmsSmsProvider( 1460): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1460): match 0:Elapsed time : 0.901 ms
,D/[CarModeFW]( 8439): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 8439): MyPlaceProvider-=============
,D/[CarModeFW]( 8439): MyPlaceProvider-=============
D/[CarModeFW]( 8439): MyPlaceProvider-=============
,D/TP/MmsSmsProvider( 1460): query,matched:13, calling pid = 8439
I/[CarModeFW]( 8439): -[snowdeer] Rec : Favorite : 21
,D/TP/MmsSmsProvider( 1460): match 13:Elapsed time : 1.325 ms
,D/[CarModeFW]( 8439): MyPlaceProvider-=============
D/[CarModeFW]( 8439): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 8439): MyPlaceProvider-==============
D/[CarModeFW]( 8439): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 8439): MyPlaceProvider-==============
D/[CarModeFW]( 8439): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 8439): MyPlaceProvider-==============
D/[CarModeFW]( 8439): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 99
,I/[CarModeFW]( 8439): -[snowdeer] Rec : CallLog : 14
,D/MessageDataHandler( 8439):  getInboxList address cursor : 17
,D/[CarMode]( 8439): [DLApplication]-GooglePlayServices SUCCESS.
,D/TP/MmsSmsProvider( 1460): query,matched:0, calling pid = 8439
V/TP/MmsSmsProvider( 1460): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1460): match 0:Elapsed time : 2.045 ms
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,E/Zygote  ( 8508): MountEmulatedStorage()
I/libpersona( 8508): KNOX_SDCARD checking this for 10046
E/Zygote  ( 8508): v2
I/libpersona( 8508): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=8508 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/[CarMode]( 8439): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/SELinux ( 8508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MessageDataHandler( 8439):  getInboxList thread cursor : 151
,I/SELinux ( 8508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/MessageDataHandler( 8439):  thread, addr result: 5
,I/[CarModeFW]( 8439): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 281
,I/[CarModeFW]( 8439): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
,D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 283
,E/SELinux ( 8508): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,D/[CarModeFW]( 8439): PushMessageService-onCreate
,I/ActivityManager(  890): Killing 7017:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/[CarMode]( 8439): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@91bcaf3d, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@827c76ef] LOCATIONS
,D/TimaKeyStoreProvider( 8508): TimaSignature is unavailable
,D/ActivityThread( 8508): Added TimaKeyStore provider
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,I/ActivityManager(  890): Killing 7052:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 7035): jangil::setProperties()
,D/[CarModeFW]( 8439): PushMessageManager-onServiceConnected
D/[CarModeFW]( 8439): PushMessageService-registerPushMessageServiceListener
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/ResourcesManager( 8508): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/bt-btif ( 3247): new conn_srvc id:26, app_id:255
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
W/bt-btif ( 3247): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3247): bta_dm_pm_ssr:2, lat:1200
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@1ba65a19
,D/SettingsProvider(  890): name = Wearable0001
W/ResourcesManager( 8508): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,E/BluetoothRemoteDevices( 3247): setRfcommConnected true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Incoming connection accepted
,W/BackupManagerService(  890): dataChanged but no participant pkg='com.android.providers.settings' uid=10112
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Incoming connection initialized (thread ID: 1233)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Waiting for incoming connections...
D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Entering thread (ID: 1233)
,W/BackupManagerService(  890): dataChanged but no participant pkg='com.android.providers.settings' uid=10112
,D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,I/ActivityManager(  890): Killing 7068:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_7017/cgroup.procs: No such file or directory
W/libprocessgroup(  890): failed to open /acct/uid_10118/pid_7052/cgroup.procs: No such file or directory
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
D/WifiP2pService(  890): discovery change broadcast false
,I/CalendarProvider2( 8508): CalendarProvider2.onCreate() called
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0002::false
D/GMFPReceiver( 7035): onServiceConnected() : 1
D/GMFPReceiver( 7035): mBluetoothHeadset = true
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_7068/cgroup.procs: No such file or directory
,D/BootupListener( 1460): ACTION_DRIVELINK
,D/SettingsProvider(  890): name = drivelink_navigation
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1001
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/BootupListener( 1460): NAVI : com.google.android.apps.maps
D/SettingsProvider(  890): name = internet_call_settings_visibility
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1001
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): onBytesRead: Read 63 bytes successfully (thread ID: 1233)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Got valid identity from [F8:95:C7:87:3C:51 G4-1]
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): onBytesWritten: 81 bytes successfully written (thread ID: 1233)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): removeThreadFromList: Removing thread with ID 1233
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Handshake thread disposed (thread ID: 1233)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnected: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 G4-1]
D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Exiting thread (ID: 1233)
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
D/io.jxcore.node.ConnectionHelper( 7427): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 7427): Entering thread (ID: 1234)
,I/io.jxcore.node.IncomingSocketThread( 7427): Local host address: localhost/127.0.0.1, port: 45946
,D/io.jxcore.node.IncomingSocketThread( 7427): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 7427): 2016-01-07T08:45:51.488Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7427): 
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1235, name: Sender)
I/io.jxcore.node.IncomingSocketThread( 7427): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7427): Exiting thread (ID: 1234)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1236, name: Receiver)
,I/art     (  890): Explicit concurrent mark sweep GC freed 54242(3MB) AllocSpace objects, 58(1123KB) LOS objects, 29% free, 38MB/54MB, paused 1.718ms total 119.608ms
,I/[CarModeFW]( 8439): -[snowdeer] Rec : Schedule : 734
,I/[CarModeFW]( 8439): -[snowdeer] Rec : During DL app : 4
,I/[CarModeFW]( 8439): -[snowdeer] Rec : Location Sharing : 1
,I/[CarModeFW]( 8439): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 8439): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 8439): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 8439): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 8439): -[snowdeer] Rec : getContactListFromHashMap - core : 0
D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 867
I/[CarModeFW]( 8439): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 8439): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 8439): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 8439): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 874
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,I/System.out( 8470): INFO:Resource not found:/Common.properties Using default values
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/bt-sdp  ( 3247): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3247): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3247): invalid rfc slot id: 6
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@3d9e2ade, channel: -1, state: INIT
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@3d9e2ade, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@331c14bf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c01378cmSocket: android.net.LocalSocket@db97ed5 impl:android.net.LocalSocketImpl@a5e16ea fd:FileDescriptor[154]
D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@db97ed5 impl:android.net.LocalSocketImpl@a5e16ea fd:FileDescriptor[154]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1232)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1232)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Exiting thread (thread ID: 1232)
,I/jxcore-log( 7427): 2016-01-07T08:45:52.252Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] failed
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.252Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] failed
I/jxcore-log( 7427): 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): shutdown (thread ID: 1232)
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@3d9e2ade, channel: -1, state: CLOSED
,I/jxcore-log( 7427): 2016-01-07T08:45:52.253Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7427): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/CalendarProvider2( 8508): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8544): MountEmulatedStorage()
,E/Zygote  ( 8544): v2
I/libpersona( 8544): KNOX_SDCARD checking this for 10149
I/libpersona( 8544): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=8544 uid=10149 gids={50149, 9997} abi=armeabi-v7a
,I/SELinux ( 8544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8544): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7427): 2016-01-07T08:45:52.596Z SendDataTCPServer.js: TCP/IP server has received 1012 bytes of data
I/jxcore-log( 7427): 
,D/TimaKeyStoreProvider( 8544): TimaSignature is unavailable
,D/ActivityThread( 8544): Added TimaKeyStore provider
,D/ResourcesManager( 8544): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 8544): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8544): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/jxcore-log( 7427): 2016-01-07T08:45:52.655Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.663Z SendDataTCPServer.js: TCP/IP server has received 3036 bytes of data
I/jxcore-log( 7427): 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8559): MountEmulatedStorage()
,E/Zygote  ( 8559): v2
I/libpersona( 8559): KNOX_SDCARD checking this for 10150
I/libpersona( 8559): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=8559 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 7101:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,I/jxcore-log( 7427): 2016-01-07T08:45:52.691Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 7427): 
,I/SELinux ( 8559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/jxcore-log( 7427): 2016-01-07T08:45:52.696Z SendDataTCPServer.js: TCP/IP server has received 5060 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.700Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.706Z SendDataTCPServer.js: TCP/IP server has received 7084 bytes of data
I/jxcore-log( 7427): 
,D/TimaKeyStoreProvider( 8559): TimaSignature is unavailable
,D/ActivityThread( 8559): Added TimaKeyStore provider
,I/jxcore-log( 7427): 2016-01-07T08:45:52.718Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 7427): 
,D/ResourcesManager( 8559): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8559): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8559): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8559): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/jxcore-log( 7427): 2016-01-07T08:45:52.728Z SendDataTCPServer.js: TCP/IP server has received 9204 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.740Z SendDataTCPServer.js: TCP/IP server has received 10216 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,I/jxcore-log( 7427): 2016-01-07T08:45:52.745Z SendDataTCPServer.js: TCP/IP server has received 12240 bytes of data
I/jxcore-log( 7427): 
,W/libprocessgroup(  890): failed to open /acct/uid_10166/pid_7101/cgroup.procs: No such file or directory
,I/jxcore-log( 7427): 2016-01-07T08:45:52.748Z SendDataTCPServer.js: TCP/IP server has received 13252 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.786Z SendDataTCPServer.js: TCP/IP server has received 17300 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.790Z SendDataTCPServer.js: TCP/IP server has received 18312 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.792Z SendDataTCPServer.js: TCP/IP server has received 19324 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.803Z SendDataTCPServer.js: TCP/IP server has received 20336 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:45:52.810Z SendDataTCPServer.js: TCP/IP server has received 21348 bytes of data
I/jxcore-log( 7427): 
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/jxcore-log( 7427): 2016-01-07T08:45:52.845Z SendDataTCPServer.js: TCP/IP server has received 25396 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.847Z SendDataTCPServer.js: TCP/IP server has received 26408 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.860Z SendDataTCPServer.js: TCP/IP server has received 27420 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.868Z SendDataTCPServer.js: TCP/IP server has received 28432 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.872Z SendDataTCPServer.js: TCP/IP server has received 29444 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.876Z SendDataTCPServer.js: TCP/IP server has received 30456 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:45:52.878Z SendDataTCPServer.js: TCP/IP server has received 31468 bytes of data
I/jxcore-log( 7427): 
,I/ActivityManager(  890): Killing 6716:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/jxcore-log( 7427): 2016-01-07T08:45:52.916Z SendDataTCPServer.js: TCP/IP server has received 35516 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.922Z SendDataTCPServer.js: TCP/IP server has received 36528 bytes of data
I/jxcore-log( 7427): 
,W/libprocessgroup(  890): failed to open /acct/uid_10012/pid_6716/cgroup.procs: No such file or directory
,I/jxcore-log( 7427): 2016-01-07T08:45:52.929Z SendDataTCPServer.js: TCP/IP server has received 37540 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.937Z SendDataTCPServer.js: TCP/IP server has received 38552 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.959Z SendDataTCPServer.js: TCP/IP server has received 39564 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:52.963Z SendDataTCPServer.js: TCP/IP server has received 40576 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:45:52.966Z SendDataTCPServer.js: TCP/IP server has received 41588 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.005Z SendDataTCPServer.js: TCP/IP server has received 46648 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.008Z SendDataTCPServer.js: TCP/IP server has received 47660 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.012Z SendDataTCPServer.js: TCP/IP server has received 48672 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.024Z SendDataTCPServer.js: TCP/IP server has received 49684 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.080Z SendDataTCPServer.js: TCP/IP server has received 50696 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:45:53.089Z SendDataTCPServer.js: TCP/IP server has received 52720 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.127Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.150Z SendDataTCPServer.js: TCP/IP server has received 54744 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.273Z SendDataTCPServer.js: TCP/IP server has received 55756 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.315Z SendDataTCPServer.js: TCP/IP server has received 56768 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.327Z SendDataTCPServer.js: TCP/IP server has received 57780 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.338Z SendDataTCPServer.js: TCP/IP server has received 58792 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.353Z SendDataTCPServer.js: TCP/IP server has received 62840 bytes of data
,I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:45:53.368Z SendDataTCPServer.js: TCP/IP server has received 63852 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.379Z SendDataTCPServer.js: TCP/IP server has received 64864 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.424Z SendDataTCPServer.js: TCP/IP server has received 72960 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7427): 2016-01-07T08:45:53.457Z SendDataTCPServer.js: TCP/IP server has received 78020 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.475Z SendDataTCPServer.js: TCP/IP server has received 85104 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:45:53.482Z SendDataTCPServer.js: TCP/IP server has received 86116 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.491Z SendDataTCPServer.js: TCP/IP server has received 87128 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.526Z SendDataTCPServer.js: TCP/IP server has received 91176 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.533Z SendDataTCPServer.js: TCP/IP server has received 92188 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.548Z SendDataTCPServer.js: TCP/IP server has received 93200 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.556Z SendDataTCPServer.js: TCP/IP server has received 94212 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.561Z SendDataTCPServer.js: TCP/IP server has received 95224 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.572Z SendDataTCPServer.js: TCP/IP server has received 96236 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.577Z SendDataTCPServer.js: TCP/IP server has received 97248 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.582Z SendDataTCPServer.js: TCP/IP server has received 98260 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:53.588Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): invalid rfc slot id: 5
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1236, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 7427): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1234
,D/io.jxcore.node.IncomingSocketThread( 7427): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1236
,D/io.jxcore.node.IncomingSocketThread( 7427): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1235
,D/io.jxcore.node.IncomingSocketThread( 7427): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1235, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 7427): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 7427): closeBluetoothSocketAndStreams
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@38073ddb, channel: 6, state: CONNECTED
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@38073ddb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2504078, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4a03351mSocket: android.net.LocalSocket@97eb7b6 impl:android.net.LocalSocketImpl@33b1dcb7 fd:FileDescriptor[152]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@97eb7b6 impl:android.net.LocalSocketImpl@33b1dcb7 fd:FileDescriptor[152]
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@38073ddb, channel: 6, state: CLOSED
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@38073ddb, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1235, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1236, name: Receiver)
,I/jxcore-log( 7427): 2016-01-07T08:45:53.724Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7427): 
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb00c rs_disc_pending=0
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-rfcomm( 3247): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3247): RFCOMM_DisconnectInd LCID:0x42
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 291, CUR = 300
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,I/jxcore-log( 7427): 2016-01-07T08:45:57.255Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:45:57.258Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,E/bt-btm  ( 3247): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 3247): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1170): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 1170): isGear1: device is not B1!
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1302): ACTION_ACL_DISCONNECTED
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@312c95a0
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/SecContentProvider(  890): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 3247): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,I/BTConnectionReceiver( 1556): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1556): Bluetooth Device Name: G4-1
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,I/Atfwd_Daemon(  324): Stop the daemon....
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/Watchdog(  890): !@Sync 19
,E/SMD     (  287): DCD ON
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/bt_vendor( 3247): op for 7
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): info:x10
,D/        ( 3247): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3247): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  890): InactiveState{ what=147494 }
D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
D/WifiP2pService(  890): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 3247): check_cod: remote_cod = 0x5a020c,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,I/BluetoothBondStateMachine( 3247): Entering PendingCommandState State
,D/btif_config_util( 3247): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3247): Failed to remove device: 08:EC:A9:50:76:27
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/HidService( 3247): getHidService(): returning com.android.bluetooth.hid.HidService@29f7321d
,D/SettingsProvider(  890): name = bluetooth_input_device_priority_08:EC:A9:50:76:27
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
D/HidService( 3247): Saved priority 08:EC:A9:50:76:27 = -1
,D/SettingsProvider(  890): name = bluetooth_a2dp_sink_priority_08:EC:A9:50:76:27
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/SettingsProvider(  890): name = bluetooth_headset_priority_08:EC:A9:50:76:27
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,I/BluetoothBondStateMachine( 3247): StableState(): Entering Off State
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage PAIRING_DEVICES
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.CLASS_CHANGED
V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Thali Test (Galaxy A3) state is 11
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0001::false
D/SettingsProvider(  890): name = Wearable0002
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Thali Test (Galaxy A3) state is 10
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/GMFPReceiver( 7035): jangil::printBTStatus()
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/SettingsProvider(  890): name = Wearable0001
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): new conn_srvc id:26, app_id:255
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3247): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2084ec24
,E/BluetoothRemoteDevices( 3247): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Incoming connection accepted
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Incoming connection initialized (thread ID: 1239)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Entering thread (ID: 1239)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): onBytesRead: Read 81 bytes successfully (thread ID: 1239)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Got valid identity from [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): onBytesWritten: 81 bytes successfully written (thread ID: 1239)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): removeThreadFromList: Removing thread with ID 1239
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Handshake thread disposed (thread ID: 1239)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onIncomingConnectionConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Exiting thread (ID: 1239)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], created successfully
,D/io.jxcore.node.ConnectionHelper( 7427): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 7427): Entering thread (ID: 1240)
,I/jxcore-log( 7427): 2016-01-07T08:46:01.999Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 7427): 
,I/io.jxcore.node.IncomingSocketThread( 7427): Local host address: localhost/127.0.0.1, port: 45946
,D/io.jxcore.node.IncomingSocketThread( 7427): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 7427): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 7427): Exiting thread (ID: 1240)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1242, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1241, name: Sender)
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 7427): 2016-01-07T08:46:02.272Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:02.273Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:02.277Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:02.278Z SendDataConnector.js: do connect now
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: We have an incoming connection with peer with ID 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 7427): connect: We already have a connection to peer with ID 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): connect: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 1243)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7427): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[157]}
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,W/bt-sdp  ( 3247): process_service_search_attr_rsp
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): new conn_srvc id:26, app_id:1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3247): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3247): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/BluetoothRemoteDevices( 3247): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onSocketConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 1243)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesWritten: 81 bytes successfully written (thread ID: 1244)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Outgoing connection initialized (*handshake* thread ID: 1244)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Exiting thread (thread ID: 1243)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Entering thread (ID: 1244)
,I/jxcore-log( 7427): 2016-01-07T08:46:03.171Z SendDataTCPServer.js: TCP/IP server has received 1012 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.244Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.256Z SendDataTCPServer.js: TCP/IP server has received 3036 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.331Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.378Z SendDataTCPServer.js: TCP/IP server has received 5060 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.392Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.408Z SendDataTCPServer.js: TCP/IP server has received 7084 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.649Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.696Z SendDataTCPServer.js: TCP/IP server has received 9108 bytes of data
I/jxcore-log( 7427): 
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,I/jxcore-log( 7427): 2016-01-07T08:46:03.730Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,I/jxcore-log( 7427): 2016-01-07T08:46:03.771Z SendDataTCPServer.js: TCP/IP server has received 11132 bytes of data
I/jxcore-log( 7427): 
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,I/jxcore-log( 7427): 2016-01-07T08:46:03.872Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 7427): 
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 7427): 2016-01-07T08:46:03.943Z SendDataTCPServer.js: TCP/IP server has received 13156 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:03.953Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.021Z SendDataTCPServer.js: TCP/IP server has received 15180 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.027Z SendDataTCPServer.js: TCP/IP server has received 16192 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.034Z SendDataTCPServer.js: TCP/IP server has received 17204 bytes of data,
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.243Z SendDataTCPServer.js: TCP/IP server has received 18216 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.261Z SendDataTCPServer.js: TCP/IP server has received 19228 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.281Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:04.393Z SendDataTCPServer.js: TCP/IP server has received 21252 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.501Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.513Z SendDataTCPServer.js: TCP/IP server has received 23276 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.519Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.575Z SendDataTCPServer.js: TCP/IP server has received 25588 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.585Z SendDataTCPServer.js: TCP/IP server has received 26600 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.591Z SendDataTCPServer.js: TCP/IP server has received 27612 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.599Z SendDataTCPServer.js: TCP/IP server has received 28624 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.668Z SendDataTCPServer.js: TCP/IP server has received 29636 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:04.681Z SendDataTCPServer.js: TCP/IP server has received 31660 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 7427): 2016-01-07T08:46:05.365Z SendDataTCPServer.js: TCP/IP server has received 32672 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:05.397Z SendDataTCPServer.js: TCP/IP server has received 33684 bytes of data
I/jxcore-log( 7427): 
,E/SMD     (  287): DCD ON
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7427): 2016-01-07T08:46:08.401Z SendDataTCPServer.js: TCP/IP server has received 34696 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:08.406Z SendDataTCPServer.js: TCP/IP server has received 35708 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:08.414Z SendDataTCPServer.js: TCP/IP server has received 36720 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:08.423Z SendDataTCPServer.js: TCP/IP server has received 37732 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:08.429Z SendDataTCPServer.js: TCP/IP server has received 38744 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:08.439Z SendDataTCPServer.js: TCP/IP server has received 39756 bytes of data
I/jxcore-log( 7427): 
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesRead: Read 81 bytes successfully (thread ID: 1244)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Handshake succeeded with [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onHandshakeSucceeded: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Exiting thread (ID: 1244)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: We have an incoming connection with peer with ID 08:EC:A9:50:76:27
,W/io.jxcore.node.ConnectionHelper( 7427): onConnected: Already connected with peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 7427): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 7427): Entering thread (ID: 1245)
,D/io.jxcore.node.OutgoingSocketThread( 7427): Server socket local port: 45768
,I/io.jxcore.node.OutgoingSocketThread( 7427): Now accepting connections...
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7427): onListeningForIncomingConnections: Outgoing connection is using port 45768 (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 7427): 2016-01-07T08:46:10.398Z SendDataConnector.js: CLIENT connected to 45768, error: null
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:10.400Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7427): 
,I/io.jxcore.node.OutgoingSocketThread( 7427): Incoming data from address: /127.0.0.1, port: 45768
,D/io.jxcore.node.OutgoingSocketThread( 7427): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 7427): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 7427): Exiting thread (ID: 1245)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1247, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1246, name: Sender)
,I/jxcore-log( 7427): 2016-01-07T08:46:10.456Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:11.360Z SendDataTCPServer.js: TCP/IP server has received 41780 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7427): 2016-01-07T08:46:12.139Z SendDataTCPServer.js: TCP/IP server has received 42792 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:13.004Z SendDataTCPServer.js: TCP/IP server has received 43804 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7427): 2016-01-07T08:46:14.719Z SendDataTCPServer.js: TCP/IP server has received 44816 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,I/jxcore-log( 7427): 2016-01-07T08:46:14.748Z SendDataTCPServer.js: TCP/IP server has received 47852 bytes of data
I/jxcore-log( 7427): 
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,I/jxcore-log( 7427): 2016-01-07T08:46:14.808Z SendDataTCPServer.js: TCP/IP server has received 48864 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:14.816Z SendDataTCPServer.js: TCP/IP server has received 49876 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:14.825Z SendDataTCPServer.js: TCP/IP server has received 50888 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:15.091Z SendDataTCPServer.js: TCP/IP server has received 51900 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.126Z SendDataTCPServer.js: TCP/IP server has received 56960 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.196Z SendDataTCPServer.js: TCP/IP server has received 58984 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.207Z SendDataTCPServer.js: TCP/IP server has received 59996 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.215Z SendDataTCPServer.js: TCP/IP server has received 62020 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:15.230Z SendDataTCPServer.js: TCP/IP server has received 63032 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.318Z SendDataTCPServer.js: TCP/IP server has received 64044 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.329Z SendDataTCPServer.js: TCP/IP server has received 65056 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.386Z SendDataTCPServer.js: TCP/IP server has received 66068 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.396Z SendDataTCPServer.js: TCP/IP server has received 67080 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.411Z SendDataTCPServer.js: TCP/IP server has received 68092 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.418Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:15.436Z SendDataTCPServer.js: TCP/IP server has received 71128 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10216,tx.queue.count:11,available:72812
,I/jxcore-log( 7427): 2016-01-07T08:46:15.739Z SendDataTCPServer.js: TCP/IP server has received 76188 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.786Z SendDataTCPServer.js: TCP/IP server has received 77200 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.794Z SendDataTCPServer.js: TCP/IP server has received 78212 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.804Z SendDataTCPServer.js: TCP/IP server has received 79224 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.815Z SendDataTCPServer.js: TCP/IP server has received 80236 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:15.832Z SendDataTCPServer.js: TCP/IP server has received 81248 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.866Z SendDataTCPServer.js: TCP/IP server has received 82260 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.927Z SendDataTCPServer.js: TCP/IP server has received 83272 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.932Z SendDataTCPServer.js: TCP/IP server has received 84284 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.989Z SendDataTCPServer.js: TCP/IP server has received 85296 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:15.999Z SendDataTCPServer.js: TCP/IP server has received 87320 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.010Z SendDataTCPServer.js: TCP/IP server has received 88332 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.023Z SendDataTCPServer.js: TCP/IP server has received 90356 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:16.036Z SendDataTCPServer.js: TCP/IP server has received 91368 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.302Z SendDataTCPServer.js: TCP/IP server has received 92380 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.338Z SendDataTCPServer.js: TCP/IP server has received 95416 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.387Z SendDataTCPServer.js: TCP/IP server has received 96428 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.395Z SendDataTCPServer.js: TCP/IP server has received 97440 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.402Z SendDataTCPServer.js: TCP/IP server has received 98452 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:16.494Z SendDataTCPServer.js: TCP/IP server has received 99464 bytes of data
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:16.501Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:16.505Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:63376
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1242, thread name: Receiver): bt socket closed, read return: -1
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
E/io.jxcore.node.OutgoingSocketThread( 7427): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1240
D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1242
D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1241
D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1241, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 7427): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@2063b38d, channel: 6, state: CONNECTED
D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@2063b38d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17369942, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ffd8d53mSocket: android.net.LocalSocket@3136a690 impl:android.net.LocalSocketImpl@3e64fb89 fd:FileDescriptor[152]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@3136a690 impl:android.net.LocalSocketImpl@3e64fb89 fd:FileDescriptor[152]
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@2063b38d, channel: 6, state: CLOSED
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@2063b38d, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1242, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1241, name: Sender)
,I/jxcore-log( 7427): 2016-01-07T08:46:16.581Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:56292
,I/jxcore-log( 7427): 2016-01-07T08:46:16.667Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7427): 
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:48196
,I/jxcore-log( 7427): 2016-01-07T08:46:17.001Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already,
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:38076
,I/jxcore-log( 7427): 2016-01-07T08:46:17.200Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:27956
,I/jxcore-log( 7427): 2016-01-07T08:46:17.898Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:17836
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,I/jxcore-log( 7427): 2016-01-07T08:46:18.328Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:8728
,I/jxcore-log( 7427): 2016-01-07T08:46:18.483Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:18.923Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:19.102Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:19.473Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:19.478Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): oneRoundDownNow
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:19.486Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:19.489Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7427): 
,D/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
,I/io.jxcore.node.OutgoingSocketThread( 7427): close
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1247,
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping sending thread...,
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1246,
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing...,
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local input stream...,
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1246, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 7427): closeBluetoothSocketAndStreams
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@2a99078e, channel: 6, state: CONNECTED
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@2a99078e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2949abaf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f079bbcmSocket: android.net.LocalSocket@1718c745 impl:android.net.LocalSocketImpl@6a20e9a fd:FileDescriptor[157]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@1718c745 impl:android.net.LocalSocketImpl@6a20e9a fd:FileDescriptor[157]
W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1247, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@2a99078e, channel: 6, state: CLOSED
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@2a99078e, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1246, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1247, name: Receiver)
,I/jxcore-log( 7427): 2016-01-07T08:46:19.547Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): ---- round done--------
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): startWithNextDevice
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): do fake peer & start
I/jxcore-log( 7427): 
I/jxcore-log( 7427): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:19.552Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:19.552Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 7427): 
I/jxcore-log( 7427): 2016-01-07T08:46:19.553Z SendDataConnector.js: do connect now
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 7427): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): connect: [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnecting: null 7C:F9:0E:34:8A:A0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 1248)
,D/BluetoothUtils( 7427): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,W/bt-btif ( 3247): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccae4c rs_disc_pending=1
,W/bt-btif ( 3247): bta_dm_check_av:0
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/bt_vendor( 3247): op for 7
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): info:x10
,D/        ( 3247): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3247): aclStateChangeCallback: Device is NULL
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb1cc rs_disc_pending=1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccae4c rs_disc_pending=1
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-sdp  ( 3247): process_service_search_attr_rsp
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/bt-btm  ( 3247): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 3247): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1170): Received android.bluetooth.device.action.ACL_DISCONNECTED,
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@312c95a0
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/SecContentProvider(  890): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 3247): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1170): isGear1: device is not B1!
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1302): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 1556): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1556): Bluetooth Device Name: Thali Test (Galaxy A3)
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 3247): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,I/BluetoothBondStateMachine( 3247): Entering PendingCommandState State
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage PAIRING_DEVICES
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED S5-1 state is 11
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
,D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,D/btif_config_util( 3247): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3247): Failed to remove device: 7C:F9:0E:34:8A:A0
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/HidService( 3247): getHidService(): returning com.android.bluetooth.hid.HidService@29f7321d
,D/SettingsProvider(  890): name = bluetooth_input_device_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
,D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/HidService( 3247): Saved priority 7C:F9:0E:34:8A:A0 = -1
,D/SettingsProvider(  890): name = bluetooth_a2dp_sink_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
,D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/SettingsProvider(  890): name = bluetooth_headset_priority_7C:F9:0E:34:8A:A0
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
,D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,I/BluetoothBondStateMachine( 3247): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED S5-1 state is 10
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb1cc rs_disc_pending=0
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/bt-btif ( 3247): new conn_srvc id:26, app_id:1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3247): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/BluetoothRemoteDevices( 3247): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onSocketConnected: [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1248)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesWritten: 81 bytes successfully written (thread ID: 1249)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Outgoing connection initialized (*handshake* thread ID: 1249)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Exiting thread (thread ID: 1248)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Entering thread (ID: 1249)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesRead: Read 63 bytes successfully (thread ID: 1249)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Handshake succeeded with [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Exiting thread (ID: 1249)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 S5-1]
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 7427): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 7427): Entering thread (ID: 1250)
,D/io.jxcore.node.OutgoingSocketThread( 7427): Server socket local port: 45672
I/io.jxcore.node.OutgoingSocketThread( 7427): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 7427): onListeningForIncomingConnections: Outgoing connection is using port 45672 (peer ID: 7C:F9:0E:34:8A:A0)
,I/jxcore-log( 7427): 2016-01-07T08:46:28.393Z SendDataConnector.js: CLIENT connected to 45672, error: null
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:28.395Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7427): 
,I/io.jxcore.node.OutgoingSocketThread( 7427): Incoming data from address: /127.0.0.1, port: 45672
,D/io.jxcore.node.OutgoingSocketThread( 7427): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 7427): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 7427): Exiting thread (ID: 1250)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1251, name: Sender)
,I/jxcore-log( 7427): 2016-01-07T08:46:28.441Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7427): 
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1252, name: Receiver)
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,E/Watchdog(  890): !@Sync 20
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:30.379Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:28584
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:30.932Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:31.052Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:7332
,I/jxcore-log( 7427): 2016-01-07T08:46:31.862Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:32.222Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:32.705Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:32.946Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:33.507Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:34.043Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,I/jxcore-log( 7427): 2016-01-07T08:46:34.973Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:34.977Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): oneRoundDownNow
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:34.983Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:34.985Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7427): 
,D/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.OutgoingSocketThread( 7427): close
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1252
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1251
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1251, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 7427): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@188f53cb, channel: 6, state: CONNECTED
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@188f53cb, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a90b7a8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b8392c1mSocket: android.net.LocalSocket@30027a66 impl:android.net.LocalSocketImpl@33d61a7 fd:FileDescriptor[154]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@30027a66 impl:android.net.LocalSocketImpl@33d61a7 fd:FileDescriptor[154]
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1252, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@188f53cb, channel: 6, state: CLOSED
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@188f53cb, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1251, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1252, name: Receiver)
,I/jxcore-log( 7427): 2016-01-07T08:46:35.060Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): ---- round done--------
I/jxcore-log( 7427): 
I/jxcore-log( 7427): startWithNextDevice
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): do fake peer & start
I/jxcore-log( 7427): 
I/jxcore-log( 7427): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 7427): 
I/jxcore-log( 7427): 2016-01-07T08:46:35.062Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:35.063Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 7427): 
I/jxcore-log( 7427): 2016-01-07T08:46:35.063Z SendDataConnector.js: do connect now
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): connect: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 7427): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1253)
,D/BluetoothUtils( 7427): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,E/SMD     (  287): DCD ON
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value 1,
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb1cc rs_disc_pending=1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb1cc rs_disc_pending=0
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3247): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/bt_vendor( 3247): op for 7
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/bt_upio ( 3247): proc btwrite assertion
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,W/bt-btif ( 3247): info:x10
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/KeyguardViewMediator( 1170): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 1170): isGear1: device is not B1!
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/BTConnectionReceiver( 1556): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage CONNECTION_COMPLETE
,I/BluetoothClassifier( 1556): Bluetooth Device Name: G4-1
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb1cc rs_disc_pending=1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/bt-btm  ( 3247): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 3247): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1170): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@312c95a0
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/SecContentProvider(  890): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 3247): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1170): isGear1: device is not B1!
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1302): ACTION_ACL_DISCONNECTED
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,I/BTConnectionReceiver( 1556): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1556): Bluetooth Device Name: S5-1
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb00c rs_disc_pending=1
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,E/SMD     (  287): DCD ON
,W/bt-sdp  ( 3247): process_service_search_attr_rsp
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 3247): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,I/BluetoothBondStateMachine( 3247): Entering PendingCommandState State
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage PAIRING_DEVICES
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
,D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,D/btif_config_util( 3247): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3247): Failed to remove device: F8:95:C7:87:3C:51
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/HidService( 3247): getHidService(): returning com.android.bluetooth.hid.HidService@29f7321d
,D/SettingsProvider(  890): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/HidService( 3247): Saved priority F8:95:C7:87:3C:51 = -1
,D/SettingsProvider(  890): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/SettingsProvider(  890): name = bluetooth_headset_priority_F8:95:C7:87:3C:51
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,I/BluetoothBondStateMachine( 3247): StableState(): Entering Off State
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0001::false
D/SettingsProvider(  890): name = Wearable0002
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): new conn_srvc id:26, app_id:1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3247): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/BluetoothRemoteDevices( 3247): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onSocketConnected: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1253)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesWritten: 81 bytes successfully written (thread ID: 1254)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Outgoing connection initialized (*handshake* thread ID: 1254)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Exiting thread (thread ID: 1253)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Entering thread (ID: 1254)
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb00c rs_disc_pending=0
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesRead: Read 63 bytes successfully (thread ID: 1254)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Handshake succeeded with [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onHandshakeSucceeded: [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Exiting thread (ID: 1254)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnected: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 G4-1]
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 7427): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 7427): Entering thread (ID: 1255)
,D/io.jxcore.node.OutgoingSocketThread( 7427): Server socket local port: 58828
,I/io.jxcore.node.OutgoingSocketThread( 7427): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 7427): onListeningForIncomingConnections: Outgoing connection is using port 58828 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 7427): 2016-01-07T08:46:45.322Z SendDataConnector.js: CLIENT connected to 58828, error: null
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:45.327Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7427): 
,I/io.jxcore.node.OutgoingSocketThread( 7427): Incoming data from address: /127.0.0.1, port: 58828
,D/io.jxcore.node.OutgoingSocketThread( 7427): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 7427): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 7427): Exiting thread (ID: 1255)
,I/jxcore-log( 7427): 2016-01-07T08:46:45.371Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7427): 
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1256, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1257, name: Receiver)
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_upio ( 3247): proc btwrite assertion
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:31128
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:46.539Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:27956
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:46.784Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:47.000Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:6704
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7427): 2016-01-07T08:46:47.541Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:47.746Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/PowerManagerService(  890): [PWL] Off : 525s ago
,I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3247, ws=null) (elapsedTime=123)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,I/jxcore-log( 7427): 2016-01-07T08:46:48.003Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:48.140Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,I/jxcore-log( 7427): 2016-01-07T08:46:48.423Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:48.596Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:48.603Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): oneRoundDownNow
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:48.610Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:48.612Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7427): 
,D/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,I/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 7427): close
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1257
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping sending thread...,
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1256,
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing...,
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local input stream...,
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1256, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 7427): closeBluetoothSocketAndStreams
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@30da654, channel: 7, state: CONNECTED
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@30da654, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e7599fd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33abd6f2mSocket: android.net.LocalSocket@cd47143 impl:android.net.LocalSocketImpl@dc8d3c0 fd:FileDescriptor[154]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@cd47143 impl:android.net.LocalSocketImpl@dc8d3c0 fd:FileDescriptor[154]
W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1257, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@30da654, channel: 7, state: CLOSED
D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@30da654, channel: 7, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1256, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1257, name: Receiver)
,I/jxcore-log( 7427): 2016-01-07T08:46:48.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): ---- round done--------
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): startWithNextDevice
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): do fake peer & start
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:48.675Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:48.675Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:48.676Z SendDataConnector.js: do connect now
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 7427): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): connect: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnecting: null 34:FC:EF:11:AE:67
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 7427): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1258)
,W/bt-btif ( 3247): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothUtils( 7427): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/bt-btm  ( 3247): tBTM_SEC_DEV:0xb3ccb00c rs_disc_pending=1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_check_av:0
,W/bt-btif ( 3247): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/bt_vendor( 3247): op for 7
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 7:24841,
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value *,
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,W/bt-btif ( 3247): info:x10
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/        ( 3247): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 3247): aclStateChangeCallback: Device is NULL
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-sdp  ( 3247): process_service_search_attr_rsp
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,E/SMD     (  287): DCD ON
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 3247): check_cod: remote_cod = 0x5a020c
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,I/BluetoothBondStateMachine( 3247): Entering PendingCommandState State
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage PAIRING_DEVICES
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 5 state is 11
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,D/btif_config_util( 3247): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/BluetoothBondStateMachine( 3247): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3247): Failed to remove device: 34:FC:EF:11:AE:67
,D/SecContentProvider(  890): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 3247): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/HidService( 3247): getHidService(): returning com.android.bluetooth.hid.HidService@29f7321d
,D/SettingsProvider(  890): name = bluetooth_input_device_priority_34:FC:EF:11:AE:67
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/HidService( 3247): Saved priority 34:FC:EF:11:AE:67 = -1
,D/SettingsProvider(  890): name = bluetooth_a2dp_sink_priority_34:FC:EF:11:AE:67
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
,D/SettingsProvider(  890): name = bluetooth_headset_priority_34:FC:EF:11:AE:67
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
,D/SettingsProvider(  890): selectionArgs: 1002
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,I/BluetoothBondStateMachine( 3247): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/[CarMode]( 8439): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Nexus 5 state is 10
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/BluetoothHeadset( 7035): BTStateChangeCB is registed
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/BluetoothHeadset( 7035): BluetoothHeadset service is binded
,D/GMFPReceiver( 7035): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 7035): jangil::setProperties()
,D/GMFPReceiver( 7035): jangil::printBTStatus()
,D/SettingsProvider(  890): name = Wearable0001
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10112
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/GMFPReceiver( 7035): ::::::::Wearable0001::false
,D/SettingsProvider(  890): name = Wearable0002
,D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
,D/SettingsProvider(  890): selectionArgs: 10112
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  890): ret = -1
D/GMFPReceiver( 7035): ::::::::Wearable0002::false
,I/ActivityManager(  890): Killing 7117:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,D/GMFPReceiver( 7035): onServiceConnected() : 1
,D/GMFPReceiver( 7035): mBluetoothHeadset = true
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,W/libprocessgroup(  890): failed to open /acct/uid_10170/pid_7117/cgroup.procs: No such file or directory
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): new conn_srvc id:26, app_id:1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,W/bt-btif ( 3247): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3247): bta_dm_pm_ssr:2, lat:1200
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,E/BluetoothRemoteDevices( 3247): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onSocketConnected: [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1258)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesWritten: 81 bytes successfully written (thread ID: 1259)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Outgoing connection initialized (*handshake* thread ID: 1259)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Exiting thread (thread ID: 1258)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Entering thread (ID: 1259)
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): onBytesRead: Read 66 bytes successfully (thread ID: 1259)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Handshake succeeded with [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onHandshakeSucceeded: [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7427): Exiting thread (ID: 1259)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnected: [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 Nexus 5]
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
,I/io.jxcore.node.ConnectionHelper( 7427): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 Nexus 5], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 7427): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 7427): Entering thread (ID: 1260)
,D/io.jxcore.node.OutgoingSocketThread( 7427): Server socket local port: 59188
,I/io.jxcore.node.OutgoingSocketThread( 7427): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 7427): onListeningForIncomingConnections: Outgoing connection is using port 59188 (peer ID: 34:FC:EF:11:AE:67)
,I/jxcore-log( 7427): 2016-01-07T08:46:52.205Z SendDataConnector.js: CLIENT connected to 59188, error: null
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:52.207Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 7427): 
,I/io.jxcore.node.OutgoingSocketThread( 7427): Incoming data from address: /127.0.0.1, port: 59188
,D/io.jxcore.node.OutgoingSocketThread( 7427): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 7427): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 7427): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 7427): Exiting thread (ID: 1260)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1262, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 7427): Entering thread (ID: 1261, name: Sender)
,I/jxcore-log( 7427): 2016-01-07T08:46:52.259Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 7427): 
,E/bt-btm  ( 3247): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 3247): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1170): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@312c95a0
,D/BtConfig.SecureMode( 3247): isSecureModeOn:false
,D/SecContentProvider(  890): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 1170): isGear1: device is not B1!
,I/BluetoothPbapService( 3247): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1302): ACTION_ACL_DISCONNECTED
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,I/BTConnectionReceiver( 1556): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1556): Bluetooth Device Name: G4-1
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_upio ( 3247): proc btwrite assertion
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:55636
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.266Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62826
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.318Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.388Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 7427): 
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43026
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,E/SMD     (  287): DCD ON
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.488Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.557Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16296
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.634Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/        ( 3247): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6396
,I/jxcore-log( 7427): 2016-01-07T08:46:53.689Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already,
,D/bt_vendor( 3247): op for 7,
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.844Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.944Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:53.947Z SendDataConnector.js: got all data for this round
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): oneRoundDownNow
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:53.951Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:53.952Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 7427): 
,D/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
,I/io.jxcore.node.OutgoingSocketThread( 7427): close
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1262
,D/io.jxcore.node.OutgoingSocketThread( 7427): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 7427): doStop: Thread ID: 1261
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1261, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 7427): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 7427): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@1586d8f9, channel: 5, state: CONNECTED
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@1586d8f9, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a1c703e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@642de9fmSocket: android.net.LocalSocket@18476bec impl:android.net.LocalSocketImpl@3dd30bb5 fd:FileDescriptor[154]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@18476bec impl:android.net.LocalSocketImpl@3dd30bb5 fd:FileDescriptor[154]
,W/io.jxcore.node.StreamCopyingThread( 7427): Either failed to read from the output stream or write to the input stream (thread ID: 1262, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 7427): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 7427): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 Nexus 5] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@1586d8f9, channel: 5, state: CLOSED
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@1586d8f9, channel: 5, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1261, name: Sender)
E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 7427): Exiting thread (ID: 1262, name: Receiver)
,W/bt-btif ( 3247): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): BT_WAKE is asserted already
,I/jxcore-log( 7427): 2016-01-07T08:46:53.995Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): ---- round done--------
I/jxcore-log( 7427): 
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
I/jxcore-log( 7427): startWithNextDevice
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): do fake peer & start
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:54.000Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:46:54.001Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
I/jxcore-log( 7427): 2016-01-07T08:46:54.002Z SendDataConnector.js: do connect now
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnecting: null 58:3F:54:73:64:C0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 7427): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 1263)
,D/BluetoothUtils( 7427): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): BT_WAKE is asserted already
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,D/bt_vendor( 3247): op for 7
,E/SMD     (  287): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): proc btwrite assertion
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/bt-btm  ( 3247): Reset sec_bd_name and name flag. (BR/EDR link)
E/bt-btm  ( 3247): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1170): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 1302): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/[CarModeFW]( 8439): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,E/BluetoothEventManager( 1302): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1170): isGear1: device is not B1!
,D/BluetoothAdapterService( 3247): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@312c95a0
D/BtConfig.SecureMode( 3247): isSecureModeOn:false
D/SecContentProvider(  890): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 3247): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,I/BTConnectionReceiver( 1556): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1556): Bluetooth Device Name: Nexus 5
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6639): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at dsf.a(PG:807)
E/HttpOperation( 6639): 	at fhk.a(PG:1126)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 8 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 10 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,E/HttpOperation( 6639): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at kff.l(PG:132)
E/HttpOperation( 6639): 	at ieo.a(PG:43)
E/HttpOperation( 6639): 	at iep.a(PG:93)
E/HttpOperation( 6639): 	at fhn.a(PG:59)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
E/ExperimentLoader( 6639): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6639): 	at kfv.a(PG:65)
E/ExperimentLoader( 6639): 	at kff.u(PG:385)
E/ExperimentLoader( 6639): 	at kfb.a(PG:29)
E/ExperimentLoader( 6639): 	at kff.l(PG:132)
E/ExperimentLoader( 6639): 	at ieo.a(PG:43)
E/ExperimentLoader( 6639): 	at iep.a(PG:93)
E/ExperimentLoader( 6639): 	at fhn.a(PG:59)
E/ExperimentLoader( 6639): 	at lex.a(PG:85)
E/ExperimentLoader( 6639): 	at lex.b(PG:132)
E/ExperimentLoader( 6639): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6639): 	at fhk.a(PG:908)
E/ExperimentLoader( 6639): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6639): 	at ihi.a(PG:22)
E/ExperimentLoader( 6639): 	at kft.a(PG:91)
E/ExperimentLoader( 6639): 	at kfv.a(PG:62)
E/ExperimentLoader( 6639): 	... 12 more
E/ExperimentLoader( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6639): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6639): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6639): 	at ihi.a(PG:19)
E/ExperimentLoader( 6639): 	... 14 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1669): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1669): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1669): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1669): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1669): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1669): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6639): [getaccountstatus] Unexpected exception
E/HttpOperation( 6639): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6639): 	at kfv.a(PG:65)
E/HttpOperation( 6639): 	at kff.u(PG:385)
E/HttpOperation( 6639): 	at kfb.a(PG:29)
E/HttpOperation( 6639): 	at ixd.a(PG:248)
E/HttpOperation( 6639): 	at ixd.b(PG:206)
E/HttpOperation( 6639): 	at ixd.a(PG:175)
E/HttpOperation( 6639): 	at fig.a(PG:78)
E/HttpOperation( 6639): 	at lex.a(PG:85)
E/HttpOperation( 6639): 	at lex.b(PG:132)
E/HttpOperation( 6639): 	at fhk.a(PG:1146)
E/HttpOperation( 6639): 	at fhk.a(PG:908)
E/HttpOperation( 6639): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6639): 	at ihi.a(PG:22)
E/HttpOperation( 6639): 	at kft.a(PG:91)
E/HttpOperation( 6639): 	at kfv.a(PG:62)
E/HttpOperation( 6639): 	... 12 more
E/HttpOperation( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6639): 	at gde.c(Unknown Source)
E/HttpOperation( 6639): 	at gde.b(Unknown Source)
E/HttpOperation( 6639): 	at ihi.a(PG:19)
E/HttpOperation( 6639): 	... 14 more
,E/EsSyncAdapterService( 6639): Sync failure
E/EsSyncAdapterService( 6639): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6639): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6639): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6639): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6639): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6639): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6639): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6639): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6639): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6639): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6639): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6639): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6639): 	... 10 more
E/EsSyncAdapterService( 6639): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6639): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6639): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6639): 	... 12 more
E/EsSyncAdapterService( 6639): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6639): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6639): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6639): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6639): 	... 14 more
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 642063, reason: 10135, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/bt_vendor( 3247): op for 7
,E/Watchdog(  890): !@Sync 21
,E/SQLiteLog( 1669): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  287): DCD ON
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,V/AlarmManager(  890): waitForAlarm result :8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13],
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,W/bt-sdp  ( 3247): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
,E/bt-btif ( 3247): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3247): invalid rfc slot id: 13
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@236b524a, channel: -1, state: INIT
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@236b524a, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3700c5bb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11355ad8mSocket: android.net.LocalSocket@3075ae31 impl:android.net.LocalSocketImpl@28144916 fd:FileDescriptor[154]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@3075ae31 impl:android.net.LocalSocketImpl@28144916 fd:FileDescriptor[154]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1263)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1263)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Exiting thread (thread ID: 1263)
,I/jxcore-log( 7427): 2016-01-07T08:47:00.465Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:00.468Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:00.471Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7427): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): shutdown (thread ID: 1263)
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@236b524a, channel: -1, state: CLOSED
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  287): DCD ON
,I/jxcore-log( 7427): 2016-01-07T08:47:05.477Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:05.480Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: RESTARTING
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
,I/jxcore-log( 7427): 2016-01-07T08:47:10.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:10.498Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:10.500Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:10.502Z SendDataConnector.js: do connect now
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 7427): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnecting: null 58:3F:54:73:64:C0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): connect: Started connecting to null in address 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 7427): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 1265)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 7427): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,D/bt_upio ( 3247): proc btwrite assertion
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): Start timer timeout, starting now...
,D/WifiP2pService(  890): InactiveState{ what=139265 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139265 }
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: STARTED
,D/WifiP2pService(  890): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  287): DCD ON
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-sdp  ( 3247): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
,E/bt-btif ( 3247): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3247): invalid rfc slot id: 14
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@1bec0297, channel: 1, state: INIT
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@1bec0297, channel: 1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24114c84, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12c5fc6dmSocket: android.net.LocalSocket@3a83e0a2 impl:android.net.LocalSocketImpl@37e43133 fd:FileDescriptor[154]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@3a83e0a2 impl:android.net.LocalSocketImpl@37e43133 fd:FileDescriptor[154]
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@1bec0297, channel: 1, state: CLOSED
,D/BluetoothUtils( 7427): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 7427): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3247): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 3247): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3247): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 3247): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 3247): db_query_execute: result 1
,D/bt_vendor( 3247): op for 7
D/bt_upio ( 3247): proc btwrite assertion
,D/BluetoothSocket( 7427): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[154]}
,E/SMD     (  287): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_vendor( 3247): op for 7
,D/bt_upio ( 3247): ..proc_btwrite_timeout..
,E/SMD     (  287): DCD ON
,W/bt-sdp  ( 3247): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
,E/bt-btif ( 3247): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3247): invalid rfc slot id: 15
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@1398acf0, channel: -1, state: INIT
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@1398acf0, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e52f269, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@56364eemSocket: android.net.LocalSocket@1226ad8f impl:android.net.LocalSocketImpl@ef3a81c fd:FileDescriptor[154]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@1226ad8f impl:android.net.LocalSocketImpl@ef3a81c fd:FileDescriptor[154]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1265)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1265)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): Exiting thread (thread ID: 1265)
,E/SMD     (  287): DCD ON
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
,I/jxcore-log( 7427): 2016-01-07T08:47:23.487Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 7427): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7427): shutdown (thread ID: 1265)
,I/jxcore-log( 7427): 2016-01-07T08:47:23.493Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:23.497Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 7427): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@1398acf0, channel: -1, state: CLOSED
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,I/jxcore-log( 7427): timeout now
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): weAreDoneNow, resultArray.length: 4
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): sendReportNow
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): done, now sending data to server
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:25.840Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): 2016-01-07T08:47:25.842Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 7427): 
,D/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 7427): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 7427): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
,I/jxcore-log( 7427): 2016-01-07T08:47:25.845Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 7427): 
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,E/SMD     (  287): DCD ON
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  890): !@Sync 22
,E/SMD     (  287): DCD ON
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 7427): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiP2pService(  890): InactiveState{ what=147494 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): P2pEnabledState{ what=147494 }
,D/WifiP2pService(  890): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 7427): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 7427): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  287): DCD ON
,E/SMD     (  287): DCD ON
,I/wpa_supplicant( 1271): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService(  890): InactiveState{ what=147477 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147477 }
,D/WifiDisplayController(  890): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
,D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/WifiDisplayController(  890): Received list of peers.
,D/WifiDisplayController(  890):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController(  890):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController(  890):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService(  890): InactiveState{ what=139283 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139283 }
D/WifiP2pService(  890): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): restart: Restarting...
,D/WifiP2pService(  890): InactiveState{ what=139307 }
D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,D/WifiP2pService(  890): InactiveState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139301 }
,D/WifiP2pService(  890): P2pEnabledState add service request
,D/WifiP2pManager( 7427): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service request added successfully
,E/SMD     (  287): DCD ON
,D/WifiP2pService(  890): InactiveState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139310 }
,D/WifiP2pService(  890): P2pEnabledState discover services
,D/WifiService(  890): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine(  890): callSECApi what=74
,D/WifiStateMachine(  890): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1271): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1271): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service discovery started successfully
,I/wpa_supplicant( 1271): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  287): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 290, CUR = 300
,I/jxcore-log( 7427): teardown
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): testSendData stopped
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): shutdown
,D/BluetoothSocket( 7427): close() in, this: android.bluetooth.BluetoothSocket@3c9f4c25, channel: 6, state: LISTENING
,D/BluetoothSocket( 7427): close() this: android.bluetooth.BluetoothSocket@3c9f4c25, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29992792, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22a4e1famSocket: android.net.LocalSocket@3e6a93ab impl:android.net.LocalSocketImpl@2da12a08 fd:FileDescriptor[153]
,D/BluetoothSocket( 7427): Closing mSocket: android.net.LocalSocket@3e6a93ab impl:android.net.LocalSocketImpl@2da12a08 fd:FileDescriptor[153]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7427): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7427): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7427): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7427): stop: Stopping services
,D/WifiP2pService(  890): InactiveState{ what=139298 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139298 }
,D/WifiP2pService(  890): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): stop: Stopping P2P device discovery...
,D/WifiP2pService(  890): InactiveState{ what=139268 }
,I/wpa_supplicant( 1271): P2P-FIND-STOPPED 
,D/WifiP2pService(  890): InactiveState{ what=147493 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147493 }
,D/WifiP2pService(  890): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7427): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7427): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7427): setState: NOT_STARTED
,D/WifiP2pService(  890): InactiveState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState{ what=139307 }
,D/WifiP2pService(  890): P2pEnabledState clear service request
,I/jxcore-log( 7427): StopBroadcasting went ok
I/jxcore-log( 7427): 
,D/WifiP2pService(  890): remove channel information from framework
,I/jxcore-log( 7427): 2016-01-07T08:47:46.860Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 7427): 
,I/io.jxcore.node.ConnectionHelper( 7427): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7427): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7427): P2P device discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 7427): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7427): Service requests cleared successfully
,I/jxcore-log( 7427): ****TEST TOOK:  ms ****
I/jxcore-log( 7427): 
,I/jxcore-log( 7427): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7427): 
,I/chromium( 7427): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime( 8755): 
D/AndroidRuntime( 8755): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8755): CheckJNI is OFF
,D/AndroidRuntime( 8755): setted country_code = Germany
D/AndroidRuntime( 8755): setted countryiso_code = DE
,D/AndroidRuntime( 8755): setted sales_code = DBT
,D/AndroidRuntime( 8755): readGMSProperty: start,
D/AndroidRuntime( 8755): readGMSProperty: already setted!!
,D/AndroidRuntime( 8755): readGMSProperty: end,
,D/AndroidRuntime( 8755): addProductProperty: start,
,E/SMD     (  287): DCD ON
,E/AffinityControl( 8755): AffinityControl: registerfunction enter
,D/AndroidRuntime( 8755): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  890): START PACKAGE DELETE: observer{307119609}
D/PackageManager(  890): pkg{<packageName>}
D/PackageManager(  890): user{0}
D/PackageManager(  890): caller{2000}
D/PackageManager(  890): flags{3}
D/PersonaManagerService(  890): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  890): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy(  890): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  890): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  890): !@killApplicatoin: 10367, uninstall pkg
,I/ActivityManager(  890): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
,I/ActivityManager(  890): Killing 7427:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
,I/ActivityManager(  890):   Force finishing activity ActivityRecord{237f1567 u0 com.test.thalitest/.MainActivity t12}
,D/FocusedStackFrame(  890): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  252): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  252): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WifiService(  890): Client connection lost with reason: 4
,W/PackageSettings(  890): Skipping PackageSetting{3d66f0a9 com.example.hello/10375} due to missing metadata
,I/ActivityManager(  890): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 4452): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 686us total 79.584ms
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1556): Explicit concurrent mark sweep GC freed 50487(2MB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 16MB/27MB, paused 3.935ms total 140.607ms
W/GeofencerStateMachine( 2138): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1858): mOCRHelper is null
E/libprocessgroup(  890): failed to kill 1 processes for processgroup 7427
,I/KLMS-2.4.503: ( 7631): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/KLMS-2.4.503: ( 7631): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1452156468057
,I/KLMS-2.4.503: ( 7631): MainReciver(): PACKAGE_REMOVED
,I/art     (  890): Explicit concurrent mark sweep GC freed 67829(4MB) AllocSpace objects, 45(915KB) LOS objects, 29% free, 38MB/54MB, paused 5.350ms total 177.813ms
I/KLMS-2.4.503: ( 7631): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     (  890): WaitForGcToComplete blocked for 51.698ms for cause Explicit
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/RegisteredServicesCache( 1450): empty dynamic service
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8785): MountEmulatedStorage()
E/Zygote  ( 8785): v2
I/libpersona( 8785): KNOX_SDCARD checking this for 10104
I/libpersona( 8785): KNOX_SDCARD not a persona
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ActivityManager(  890): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8785 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/SELinux ( 8785): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8785): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8785): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/EnterpriseDeviceManagerService(  890): Package has changed for user 0
D/EnterpriseDeviceManagerService(  890): Admin package name: com.google.android.gms
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider( 8785): TimaSignature is unavailable
,D/ActivityThread( 8785): Added TimaKeyStore provider
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/SurfaceWidgetView( 1480): destroyHardwareResources():962927056
,V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  890): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 8785): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Launcher( 1480): onRestart, Launcher: 948662783
D/Launcher( 1480): onStart, Launcher: 948662783
D/Launcher.HomeView( 1480): onStart
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2235): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2235): [237392/6] SurfaceWidget drawing first frame
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/SurfaceFlinger(  252): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/elm:14451( 8785): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8785): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8785): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/art     (  890): Explicit concurrent mark sweep GC freed 14638(700KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 38MB/54MB, paused 7.672ms total 325.978ms
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/InputMethodManagerService(  890): Got RemoteException sending setActive(false) notification to pid 7427 uid 10367
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/elm:14451( 8785): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 8785): ElmAgentService : onCreate()
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/elm:14451( 8785): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,E/Zygote  ( 8804): MountEmulatedStorage()
E/Zygote  ( 8804): v2
I/libpersona( 8804): KNOX_SDCARD checking this for 10017
,I/libpersona( 8804): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8804 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/elm:14451( 8785): MainReceiver.listeningToPackageRemoved()
,D/elm:14451( 8785): MDMBridge.getInstance()
D/elm:14451( 8785): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 8804): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8804): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8804): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14451( 8785): MDMBridge.getAllLicenseInfoFromSDK()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{238a776b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:692914
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 8804): TimaSignature is unavailable
,D/ActivityThread( 8804): Added TimaKeyStore provider
,D/elm:14451( 8785): ElmAgentService : onDestroy().
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  890): Killing 6263:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,D/ResourcesManager( 8804): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/RCPManagerService(  890): PackageReceiver onReceive()
,I/HarmonyEASService(  890): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  890): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  890): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  890): uID is 10367
V/EnterpriseBillingPolicy(  890): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - start - com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8804): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8804): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8804): onReceive() : package name is not s health. Return !!!
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  890): removeObsoleteFile: deleting file=12_task.xml
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,I/PCWCLIENTTRACE_PushUtil( 6784): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6784): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6784): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,V/HeadsetService( 3247): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3247): Disconnected process message: 10
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,E/Zygote  ( 8821): MountEmulatedStorage()
I/libpersona( 8821): KNOX_SDCARD checking this for 10034
E/Zygote  ( 8821): v2
I/libpersona( 8821): KNOX_SDCARD not a persona
,D/PackageManager(  890): delete codoeFile: 
D/PackageManager(  890): result of delete: 1{307119609}
I/ActivityManager(  890): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8821 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 7206:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/SELinux ( 8821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  890): failed to open /acct/uid_10114/pid_6263/cgroup.procs: No such file or directory
,I/SELinux ( 8821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
E/SELinux ( 8821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 801us total 25.246ms
,D/AndroidRuntime( 8755): Shutting down VM
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 500us total 18.035ms
,D/TimaKeyStoreProvider( 8821): TimaSignature is unavailable
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ActivityThread( 8821): Added TimaKeyStore provider
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 395us total 15.414ms
,D/ResourcesManager( 8821): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10044/pid_7206/cgroup.procs: No such file or directory
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FeatureConfig( 8821): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  890): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  890): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8821): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 8821): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8821): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8821): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8821): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8821): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
,D/ResourcesManager( 8821): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk,
,W/ResourcesManager( 8821): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 8821): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
,W/ResourcesManager( 8821): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.,
,W/ResourcesManager( 8821): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 8821): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8821): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8821): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 8821): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8821): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/EventHub(  890): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 8821): Fatal signal 7 (SIGBUS), code 2, fault addr 0xaf8416cc in tid 8821 (pp.galaxyfinder)
,E/audit_log( 2044): File locking failed. error= Bad file number
,E/audit_log( 2044): File locking failed. error= Bad file number
,I/EventHub(  890): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  890): Process com.samsung.android.app.galaxyfinder (pid 8821)(adj 0) has died(160,548)
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8842): MountEmulatedStorage()
I/libpersona( 8842): KNOX_SDCARD checking this for 10035
E/Zygote  ( 8842): v2
I/libpersona( 8842): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8842 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Zygote  (  315): Process 8821 exited due to signal (7)
,I/EventHub(  890): Removing device '/dev/input/event6' due to inotify event
,I/SELinux ( 8842): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8842): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8842): TimaSignature is unavailable
,D/ActivityThread( 8842): Added TimaKeyStore provider
,I/EventHub(  890): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager( 8842): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 8842): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 8842): Unable to setupGraphicsSupport due to missing cache directory
,W/        ( 8842): Zip: failed reading lfh name from offset 418254
,D/AndroidRuntime( 8842): Shutting down VM
,F/libc    ( 8842): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73397151 in tid 8842 (oid.app.shealth)
,F/libc    ( 8842): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2044): File locking failed. error= Bad file number
,I/EventHub(  890): Removing device '/dev/input/event8' due to inotify event
,I/ActivityManager(  890): Process com.sec.android.app.shealth (pid 8842)(adj 0) has died(161,548)
,F/libc    ( 5102): Fatal signal 7 (SIGBUS), code 2, fault addr 0x781e4a00 in tid 5102 (om.sec.spp.push)
,F/libc    ( 5102): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2044): File locking failed. error= Bad file number
,I/EventHub(  890): Removing device '/dev/input/event9' due to inotify event
,I/ActivityManager(  890): Process com.sec.spp.push (pid 5102)(adj 0) has died(167,549)
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/Zygote  (  315): Process 8842 exited due to signal (7)
,I/EventHub(  890): Removing device '/dev/input/event10' due to inotify event
E/Zygote  ( 8862): MountEmulatedStorage()
I/libpersona( 8862): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8862): v2
I/libpersona( 8862): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8862 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Zygote  (  315): Process 5102 exited due to signal (7)
,I/EventHub(  890): Removing device '/dev/input/event11' due to inotify event
,I/SELinux ( 8862): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 8862): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8862): TimaSignature is unavailable
,D/ActivityThread( 8862): Added TimaKeyStore provider
,D/ResourcesManager( 8862): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8862): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8862): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 8862): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb395b756 in tid 8862 (moteNotiProcess)
,F/libc    ( 8862): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2044): File locking failed. error= Bad file number
,I/qdhwcomposer(  252): handle_blank_event: dpy:0 panel power state: 0

```
