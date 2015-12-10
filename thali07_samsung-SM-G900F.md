#### Test 50650278b86327b_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
I/art     ( 1642): Explicit concurrent mark sweep GC freed 29113(1833KB) AllocSpace objects, 16(1296KB) LOS objects, 40% free, 17MB/29MB, paused 669us total 68.013ms
V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/Books/Books.apk
V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7341): null auth token
D/PanelView( 1169): There is/are notification(s) 
I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
I/qtaguid ( 7341): Untagging socket 34
W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
W/ApiaryClient( 7341): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5947023664597070478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
--------- beginning of system
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AndroidRuntime( 7390): 
D/AndroidRuntime( 7390): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7390): CheckJNI is OFF
D/AndroidRuntime( 7390): setted country_code = Germany
D/AndroidRuntime( 7390): setted countryiso_code = DE
D/AndroidRuntime( 7390): setted sales_code = DBT
D/AndroidRuntime( 7390): readGMSProperty: start
D/AndroidRuntime( 7390): readGMSProperty: already setted!!
D/AndroidRuntime( 7390): readGMSProperty: end
D/AndroidRuntime( 7390): addProductProperty: start
E/BooksSync( 7341): Soft error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5947023664597070478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7341): Sync error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5947023664597070478&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7341): Finished books sync
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 68533, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  889): Killing 6569:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PowerManagerService(  889): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1169 (0x0)
D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  889): failed to open /acct/uid_10075/pid_6569/cgroup.procs: No such file or directory
E/AffinityControl( 7390): AffinityControl: registerfunction enter
D/AndroidRuntime( 7390): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  889): inState():  stateMachine is null !!
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  889): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  889): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService(  889): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  889): mDVFSHelper.acquire()
I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=404, Starting com.test.thalitest
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SQLiteSecureOpenHelper( 3541): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3541): getDatabaseLocked(b,b,pwd)...
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/AndroidRuntime( 7390): Shutting down VM
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 22
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/GAV2    ( 7341): Thread[GAThread,5,main]: No campaign data found.
D/LightsService(  889): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 889) 
D/LightsService(  889): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  889): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  889): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
I/PhoneStatusBar( 1169): Icon Only
D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager(  889): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 3810): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3810): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
V/BitmapFactory( 1169): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
E/Zygote  ( 7422): MountEmulatedStorage()
I/libpersona( 7422): KNOX_SDCARD checking this for 10367
E/Zygote  ( 7422): v2
I/libpersona( 7422): KNOX_SDCARD not a persona
D/KnoxNotification( 1169): ----- inflateViews : modified publicViewLocal -----
I/ActivityManager(  889): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7422 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7422): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 1169): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1169): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1169): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@27c9f63c
D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
D/TimaKeyStoreProvider( 7422): TimaSignature is unavailable
D/ActivityThread( 7422): Added TimaKeyStore provider
V/ActivityManager(  889): Display changed displayId=0
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  889): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager( 7422): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SSRM:m  (  889): SIOP:: AP = 360, PST = 433, CUR = 300
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/WebViewFactory( 7422): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7422): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/LibraryLoader( 7422): Loading: webviewchromium
,I/LibraryLoader( 7422): Time to load native libraries: 2 ms (timestamps 7658-7660)
,I/LibraryLoader( 7422): Expected native library version number "",actual native library version number ""
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/WebViewChromiumFactoryProvider( 7422): Binding Chromium to main looper Looper (main, tid 1) {253e44e9}
,I/LibraryLoader( 7422): Expected native library version number "",actual native library version number ""
I/chromium( 7422): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7422): Initializing chromium process, renderers=0
,W/art     ( 7422): Attempt to remove local handle scope entry from IRT, ignoring
,V/AlarmManager(  889): waitForAlarm result :4
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/chromium( 7422): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7422): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7422): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,E/SMD     (  288): DCD ON
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Adreno-EGL( 7422): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7422): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7422): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7422): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7422): Remote Branch: 
I/Adreno-EGL( 7422): Local Patches: 
I/Adreno-EGL( 7422): Reconstruct Branch: 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,W/chromium( 7422): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7422): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/art     ( 7422): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7422): onDetachedFromWindow called when already detached. Ignoring
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SystemWebViewEngine( 7422): CordovaWebView is running on device made by: samsung
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/art     ( 7422): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 7422): Attempt to remove local handle scope entry from IRT, ignoring
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
,D/Activity( 7422): performCreate Call secproduct feature valuefalse
D/Activity( 7422): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/OpenGLRenderer( 7422): Render dirty regions requested: true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6672): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6672): [1] 5.onFinished: Scheduling replication attempt 2.
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  889): post active user change for 0
D/KnoxTimeoutHandler(  889): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  889): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SurfaceFlinger(  249): id=16 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/OpenGLRenderer( 7422): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/OpenGLRenderer( 7422): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7422): Enabling debug mode 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/InputMethodManagerService(  889): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/Adreno-ES20( 7422): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7422): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  889): Displayed com.test.thalitest/.MainActivity: +744ms
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7422): Timeline: Activity_idle id: android.os.BinderProxy@1c985ea0 time:98197
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
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
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/9)
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
D/CustomFrequencyManagerService(  889): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  889): mDVFSHelper.release()
I/Timeline(  889): Timeline: Activity_windows_visible id: ActivityRecord{3bddf366 u0 com.test.thalitest/.MainActivity t12} time:98262
,D/CustomFrequencyManagerService(  889): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  pkgName : ACTIVITY_RESUME_BOOSTER@10
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
,D/JsMessageQueue( 7422): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/chromium( 7422): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7422): 
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
,D/LockPatternUtilsCache( 1169): value : false
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
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,D/CustomFrequencyManagerService(  889): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  tag : ACTIVITY_RESUME_BOOSTER@10
,D/jxcore_app_log( 7422): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259363584
,D/JX-Cordova( 7422): jxcore cordova android initializing
,W/jxcore-log( 7422): Initializing JXcore engine
,W/jxcore-log( 7422): JXcore engine is ready
,W/jxcore-log( 7422): Starting JXcore engine
,E/auditd  ( 2184): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  889): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  889): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7479): MountEmulatedStorage()
I/libpersona( 7479): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7479): v2
I/libpersona( 7479): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7479 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7479): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7479): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7479): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7479): TimaSignature is unavailable
,D/ActivityThread( 7479): Added TimaKeyStore provider
,D/ResourcesManager( 7479): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7479):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7479):  SeDenialReceiver : File path = null
,I/ActivityManager(  889): Killing 6592:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,W/jxcore-log( 7422): Platform android
W/jxcore-log( 7422): 
W/jxcore-log( 7422): Process ARCH arm
W/jxcore-log( 7422): 
,W/libprocessgroup(  889): failed to open /acct/uid_1000/pid_6592/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,E/SMD     (  288): DCD ON
,D/PowerManagerService(  889): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  889): getFinalBrightness : 1 -> 1
D/PowerManagerService(  889): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  889): getFinalBrightness : 1 -> 1
,D/lights  (  889): lcd : 1 +
,D/lights  (  889): lcd : 1 -
,D/DisplayPowerController(  889): getFinalBrightness : 1 -> 1
,D/TaskPersister(  889): removeObsoleteFile: deleting file=11_task_thumbnail.png
,I/jxcore-log( 7422): JXcore Cordova bridge is ready!
I/jxcore-log( 7422): 
,W/jxcore-log( 7422): JXcore engine is started
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/jxcore-log( 7422): Toggling radios to true
I/jxcore-log( 7422): 
,D/BluetoothAdapter( 7422): enable()
,D/BluetoothAdapter( 7422): enable(): BT is already enabled..!
,D/WifiService(  889): New client listening to asynchronous messages
,I/WifiManager( 7422): packageName : com.test.thalitest
,D/SecContentProvider(  889): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  889): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  889): mCursor = null
D/WifiService(  889): setWifiEnabled: true pid=7422, uid=10367
E/WifiService(  889): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  889): Permission Denial: getCurrentUser() from pid=7422, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  889): Failed getting userId using ActivityManagerNative
W/WifiService(  889): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7422, uid=10367 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  889): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  889): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  889): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  889): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  889): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  889): name = wifi_on
,I/WifiService(  889): disconnect: pid=7422, uid=10367
,I/wpa_supplicant( 1290): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7422): Radios toggled
I/jxcore-log( 7422): 
,I/jxcore-log( 7422): Got Device Bluetooth address: B0:C5:59:3F:75:69
I/jxcore-log( 7422): 
,I/jxcore-log( 7422): Perf Test app loaded loaded
I/jxcore-log( 7422): 
,I/chromium( 7422): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/wpa_supplicant( 1290): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1290): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  889): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1290): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1290): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1290): Disconnected - do not scan
,I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  889): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  889): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  889): handleNetworkDisconnect "NG700" nid=0
,E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log( 7422): check test folder
I/jxcore-log( 7422): 
,I/jxcore-log( 7422): found test : ./testFindPeers.js
I/jxcore-log( 7422): 
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  889): InactiveState{ what=143375 }
,D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/CommandListener(  282): Clearing all IP addresses on wlan0
,I/jxcore-log( 7422): found test : ./testSendData.js
I/jxcore-log( 7422): 
,E/WifiStateMachine(  889): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,V/NativeCrypto( 1642): Read error: ssl=0xaec22200: I/O error during system call, Connection timed out
E/ConnectivityService(  889): updateNetworkInfo()
,D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
,V/NativeCrypto( 1642): SSL shutdown failed: ssl=0xaec22200: I/O error during system call, Broken pipe
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  889): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1290): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1290): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1290): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1290): First Scan Start
,E/WifiStateMachine(  889): ConnectModeState: Network connection lost 
,I/wpa_supplicant( 1290): Scan requested (ret=0) - scan timeout 30 seconds
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  889): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  889): InactiveState{ what=143375 }
D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): ValidatedState{ when=-6ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=-11ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Validated
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/CommandListener(  282): Clearing all IP addresses on wlan0
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/ConnectivityService(  889): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  889): calling update connectivity
D/EntConnectivity(  889): Not allowed due to - mEnabled false
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
D/ConnectivityService(  889): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/Nat464Xlat(  889): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
,D/ConnectivityService(  889): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  889): updateConfiguredNetworkExpiration - currTime: 1449756658262
D/WifiStateMachine(  889): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
,D/CSLegacyTypeTracker(  889): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker(  889): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1471): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1301): Starting #6
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ConnectivityService(  889): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
,E/WifiStateMachine(  889): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  889): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  889): NetworkAgent: NetworkAgent channel lost
V/NetworkStats(  889): updateIfacesLocked()
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
V/NetworkStats(  889): performPollLocked(flags=0x1)
,D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  889): UpdateStatsForKnox
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/Hs20UtilService( 1301): Message received 5007
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
V/NetworkStats(  889): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,E/ConnectivityService(  889): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/ConnectivityService(  889): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe18:8b78/64,192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1169): updateDataNetType()
,D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,E/WifiStateMachine(  889): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  889): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  889): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
V/NetworkStats(  889): performPollLocked() took 16ms
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,E/WifiStateMachine(  889): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  889): mCursor = null
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  889): mCursor = null
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,I/Choreographer( 7422): Skipped 75 frames!  The application may be doing too much work on its main thread.
,I/Hs20UtilService( 1301): Starting #7
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,I/chromium( 7422): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/ApplicationPolicy(  889): updateDataUsageMap
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1920): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  889): MasterInitialState.processMessage what=3
,D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  889): getSBEnabled() enabled =false
,D/SmartBondingService(  889): getSBEnabled() enabled =false
,D/SmartBondingService(  889): getSBEnabled() enabled =false
I/CLocInfoService(  889): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
,I/CLocInfoService(  889): CLoinfo wifi false
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7169): [#DCM#] [DCM_Performance] onReceive completed in time  3514 microsec. 
,W/SLocation(  889): No Active Data Connection
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5374): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/SystemBroadcastReceiver( 7169): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7169): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 7169): [#DCM#] setIsConnectedForExtractors 
,I/PCWCLIENTTRACE_PushUtil( 6784): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6784): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6784): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): noConnectivity : true
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7555): MountEmulatedStorage()
E/Zygote  ( 7555): v2
I/libpersona( 7555): KNOX_SDCARD checking this for 10002
I/libpersona( 7555): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7555 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7555): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 676us total 27.261ms
,D/TimaKeyStoreProvider( 7555): TimaSignature is unavailable
,D/ActivityThread( 7555): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 403us total 16.409ms
,D/ResourcesManager( 7555): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 423us total 17.117ms
,I/ActivityManager(  889): Killing 6626:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7572): MountEmulatedStorage()
,E/Zygote  ( 7572): v2
I/libpersona( 7572): KNOX_SDCARD checking this for 1000
I/libpersona( 7572): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7572 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup(  889): failed to open /acct/uid_1000/pid_6626/cgroup.procs: No such file or directory
I/SELinux ( 7572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7572): TimaSignature is unavailable
,D/ActivityThread( 7572): Added TimaKeyStore provider
,D/ResourcesManager( 7572): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 7572): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7572): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 1290): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 1290): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1290): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 1290): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  889): [1,449,756,659,319 ms] noteScanEnd no scan source
,E/WifiStateMachine(  889): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@227fa800 sup_state=SCANNING debouncing=false
,I/CLocInfoService(  889): External Intent Received android.net.wifi.SCAN_RESULTS
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  889): setDetailed state send new extra info0x
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
,I/DIAGMON_AGENT( 7572): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7572): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7572): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7572): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 1290): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1290): Associated with C0.AA.48
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
,I/wpa_supplicant( 1290): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  889): setDetailed state send new extra info"NG700"
,I/wpa_supplicant( 1290): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1290): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/ActivityManager(  889): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7588 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1290): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1290): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1290): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,E/Zygote  ( 7588): MountEmulatedStorage()
,E/Zygote  ( 7588): v2
I/libpersona( 7588): KNOX_SDCARD checking this for 10011
I/wpa_supplicant( 1290): Blacklist: Clear (temp) 
I/libpersona( 7588): KNOX_SDCARD not a persona
I/wpa_supplicant( 1290): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  889): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  889): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  889): Network connection established
,D/WifiNative-HAL(  889): callSECApiVoid - ID [50]
,E/WifiStateMachine(  889): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine(  889): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  889): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  889): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService(  889): Got NetworkAgent Messenger
,D/ConnectivityService(  889): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  889): updateNetworkInfo()
E/WifiStateMachine(  889): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  889): NetworkAgent connected
,E/WifiStateMachine(  889): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  889): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  889): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  889): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/SELinux ( 7588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7588): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  282): Setting iface cfg
,E/WifiStateMachine(  889): Start Dhcp Watchdog 2
D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
E/WifiStateMachine(  889): calculateWifiScore() report new score 60
I/WifiStateMachine(  889): calculateWifiScore : sendNetworkScore in!
I/WifiStateMachine(  889): calculateWifiScore : sendNetworkScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  889): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,D/TimaKeyStoreProvider( 7588): TimaSignature is unavailable
,D/ActivityThread( 7588): Added TimaKeyStore provider
,D/ResourcesManager( 7588): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  889): Killing 6747:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/FOTA_Client( 7588): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7588): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  889): do suspend false
,I/FOTA_Client( 7588): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/SecContentProvider2(  889): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  889): mCursor = null
D/WifiP2pService(  889): InactiveState{ what=143375 }
,D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
,I/FOTA_Client( 7588): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7588): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  889): failed to open /acct/uid_10015/pid_6747/cgroup.procs: No such file or directory
,E/Zygote  ( 7605): MountEmulatedStorage()
E/Zygote  ( 7605): v2
I/libpersona( 7605): KNOX_SDCARD checking this for 10019
I/libpersona( 7605): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7605 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7605): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  889): Killing 6768:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,I/SELinux ( 7605): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7605): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7605): TimaSignature is unavailable
,D/ActivityThread( 7605): Added TimaKeyStore provider
,D/ResourcesManager( 7605): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7605): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7605): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756659681
,I/KLMS-2.4.503: ( 7605): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,W/libprocessgroup(  889): failed to open /acct/uid_10016/pid_6768/cgroup.procs: No such file or directory
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7605): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7605): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  889): Killing 6538:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7620): MountEmulatedStorage()
E/Zygote  ( 7620): v2
I/libpersona( 7620): KNOX_SDCARD checking this for 10037
I/libpersona( 7620): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7620 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  889): failed to open /acct/uid_10034/pid_6538/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7620): TimaSignature is unavailable
,D/ActivityThread( 7620): Added TimaKeyStore provider
,E/Watchdog(  889): !@Sync 3
,D/ResourcesManager( 7620): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/SMD     (  288): DCD ON
,E/dhcpcd  ( 7635): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SO_AGENT( 7620): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,I/dhcpcd  ( 7635): version 5.5.6 starting
,E/dhcpcd  ( 7635): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5268): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6825): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6825): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6825): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6825): [SLFUCHKMGR] constructor called
,E/SPPClientService( 5268): [[SystemStateMonitorService]] No Active Internet
,I/dhcpcd  ( 7635): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7635): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7635): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7635): bssid match
,I/dhcpcd  ( 7635): wlan0: rebinding lease of 192.168.1.135
,I/SA      ( 6825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6825): [OR] == isSIMCardReady false ==
,I/SA      ( 6825): [SCU] == networkStateCheck == false
,I/SA      ( 6825): [OR] onReceive END
,I/ActivityManager(  889): Killing 4777:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7644): MountEmulatedStorage()
I/libpersona( 7644): KNOX_SDCARD checking this for 10071
E/Zygote  ( 7644): v2
I/libpersona( 7644): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7644 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7644): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7644): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7644): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  889): failed to open /acct/uid_10035/pid_4777/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7644): TimaSignature is unavailable
,D/ActivityThread( 7644): Added TimaKeyStore provider
,D/ResourcesManager( 7644): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7644): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7644): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/AlarmManager(  889): waitForAlarm result :8
,W/ResourcesManager( 7644): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/comsamsunglog( 7644): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7644): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7644): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7644): [KK AccuPhone]>>> ==============================================================================================
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/comsamsunglog( 7644): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7644): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7644): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7644): [KK AccuPhone]>>> ==============================================================================================
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider(  889): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  889): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  889): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  889): selectionArgs: false
D/SettingsProvider(  889): selectionArgs: 10071
D/SecContentProvider(  889): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  889): ret = -1
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7644): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7644): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7644): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
,D/accuweather( 7644): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7644): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7644): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7644): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7644): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1321): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7644): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7644): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7666): MountEmulatedStorage()
,E/Zygote  ( 7666): v2
I/libpersona( 7666): KNOX_SDCARD checking this for 1000
,I/libpersona( 7666): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7666 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6084:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  889): failed to open /acct/uid_10042/pid_6084/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7666): TimaSignature is unavailable
,D/ActivityThread( 7666): Added TimaKeyStore provider
,D/ResourcesManager( 7666): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7666): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7666): premStatus:2
,I/KnoxUsageLogPro( 7666): isEulaShown : false
I/KnoxUsageLogPro( 7666): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7684): MountEmulatedStorage()
,E/Zygote  ( 7684): v2
I/libpersona( 7684): KNOX_SDCARD checking this for 10088
I/libpersona( 7684): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7684 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 5718:com.android.mms/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7684): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7684): TimaSignature is unavailable
,D/CountryDetector(  889): No listener is left
,D/ActivityThread( 7684): Added TimaKeyStore provider
,D/ResourcesManager( 7684): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  889): failed to open /acct/uid_10050/pid_5718/cgroup.procs: No such file or directory
,I/ActivityManager(  889): Killing 6846:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,D/Headlines( 5521): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5521): getCountryCode(): countryCode = DE
,D/Headlines( 5521): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5521): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5521): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5521): requestUpdateNewsWelcomeCard !!! no welcome card
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7700): MountEmulatedStorage()
I/libpersona( 7700): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7700): v2
I/libpersona( 7700): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7700 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7700): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7700): TimaSignature is unavailable
,D/ActivityThread( 7700): Added TimaKeyStore provider
,W/libprocessgroup(  889): failed to open /acct/uid_10051/pid_6846/cgroup.procs: No such file or directory
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7700): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7700): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7700): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7700): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7700): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7700): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7700): Loading: webviewchromium
,I/LibraryLoader( 7700): Time to load native libraries: 6 ms (timestamps 4973-4979)
,I/LibraryLoader( 7700): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7700): Binding Chromium to main looper Looper (main, tid 1) {22ac57cf}
,I/LibraryLoader( 7700): Expected native library version number "",actual native library version number ""
,I/chromium( 7700): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7700): Initializing chromium process, renderers=0
,W/art     ( 7700): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7700): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7700): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7700): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7700): Requires BLUETOOTH permission
,I/Adreno-EGL( 7700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7700): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7700): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7700): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7700): Remote Branch: 
I/Adreno-EGL( 7700): Local Patches: 
I/Adreno-EGL( 7700): Reconstruct Branch: 
,I/NSApplication( 7700): Starting up...
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7758): MountEmulatedStorage()
E/Zygote  ( 7758): v2
I/libpersona( 7758): KNOX_SDCARD checking this for 10138
I/libpersona( 7758): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7758 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6863:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,I/SELinux ( 7758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  889): failed to open /acct/uid_10058/pid_6863/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7758): TimaSignature is unavailable
,D/ActivityThread( 7758): Added TimaKeyStore provider
,I/dhcpcd  ( 7635): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,D/ResourcesManager( 7758): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7758): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7758): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7758): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7635): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/QuickConnect( 7758): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7758): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7758): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7787): MountEmulatedStorage()
,E/Zygote  ( 7787): v2
I/libpersona( 7787): KNOX_SDCARD checking this for 10163
I/libpersona( 7787): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7787 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  889): Killing 6287:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
,I/SELinux ( 7787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  889): failed to open /acct/uid_1000/pid_6287/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7787): TimaSignature is unavailable
,D/ActivityThread( 7787): Added TimaKeyStore provider
,D/ResourcesManager( 7787): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7787): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7787): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7787): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7787): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/WifiP2pService(  889): InactiveState{ what=143375 }
D/WifiP2pService(  889): P2pEnabledState{ what=143375 }
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  889): WifiStateMachine DHCP successful
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,E/Zygote  ( 7828): MountEmulatedStorage()
E/Zygote  ( 7828): v2
I/libpersona( 7828): KNOX_SDCARD checking this for 10078
I/libpersona( 7828): KNOX_SDCARD not a persona
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,I/ActivityManager(  889): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7828 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,E/WifiStateMachine(  889): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  889): Not connected state, yet.
E/WifiStateMachine(  889): VerifyingLinkState enter
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
I/art     (  315): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 434us total 17.980ms
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,I/SELinux ( 7828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/WifiStateMachine(  889): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  889): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  889): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  889): callSECApiInt - ID [210]
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 396us total 12.358ms
E/WifiStateMachine(  889): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/ConnectivityService(  889): updateNetworkInfo()
,D/ConnectivityService(  889): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  889): Adding iface wlan0 to network 503
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  889): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.SingDnsChecker(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  889): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,I/SELinux ( 7828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 403us total 14.388ms
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,E/SELinux ( 7828): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,E/WifiStateMachine(  889): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  889): Now, connected state.
E/WifiStateMachine(  889): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine(  889): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
I/WifiTrafficPoller(  889): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  889): mBoosterFLAG : 0
,I/WifiTrafficPoller(  889): current booster mode : FullMode
,D/WifiNative-HAL(  889): callSECApiVoid - ID [212]
,I/CLocInfoService(  889): External Intent Received android.net.wifi.STATE_CHANGE
D/ConnectivityService(  889): Adding Route [fe80::/64 -> :: wlan0] to network 503
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  889): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,E/WifiStateMachine(  889): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  889): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  889): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  889): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  889): updateSourceRoutes : add src route for:192.168.1.135
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/        (  282): QcRouteController
,D/TimaKeyStoreProvider( 7828): TimaSignature is unavailable
,E/WifiStateMachine(  889): ConnectedState Enter  mScreenOn=true scanperiod=20000
,I/WifiStateMachine(  889): REQUEST_POWER_SAVE_ON
,D/ActivityThread( 7828): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,V/        (  282): QcRouteController
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,I/ActivityManager(  889): Killing 6887:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/        (  282): QcRouteController
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/        (  282): QcRouteController
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7479): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7479): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7479): StateMachine : Current State = 1
,V/        (  282): QcRouteController
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/        (  282): QcRouteController
V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 7787): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  889): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Nat464Xlat(  889): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
,D/ConnectivityService(  889): ignoring duplicate network state non-change
E/ConnectivityService(  889): updateNetworkInfo()
D/ConnectivityService(  889): ignoring duplicate network state non-change
E/ConnectivityService(  889): updateNetworkInfo()
,D/ConnectivityService(  889): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  889): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
D/ConnectivityService(  889): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  889):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889): currentScore = 0, newScore = 60
,D/ConnectivityService(  889):    accepting network in place of null
D/ConnectivityService(  889): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  889): Validated
D/TelephonyNetworkFactory( 1471): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  889): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  889): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/libprocessgroup(  889): failed to open /acct/uid_10098/pid_6887/cgroup.procs: No such file or directory
,D/ConnectivityService(  889): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  889): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/NetworkStats(  889): updateIfacesLocked()
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
V/NetworkStats(  889): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  889): UpdateStatsForKnox
,D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
V/NetworkStats(  889): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/ConnectivityService(  889): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
D/ConnectivityService(  889): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  889):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  889):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  889): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  889): calling update connectivity
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  889): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524290
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/art     (  889): Explicit concurrent mark sweep GC freed 79021(4MB) AllocSpace objects, 13(1813KB) LOS objects, 29% free, 37MB/53MB, paused 11.872ms total 158.461ms
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
,D/SecurityLogAgent( 7479): StateMachine : Changed Current State = 1
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/NtpTrustedTime(  889): currentTimeMillis() cache hit
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
I/ActivityManager(  889): Killing 6946:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,V/NetworkStats(  889): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  889): currentTimeMillis() cache hit
,D/ResourcesManager( 7828): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/com.peel.receiver.ConnectivityActionReceiver( 5626): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): last run: 1449746146708 -- System.currentTimeMillis()-last_run: 10515413
,D/com.peel.receiver.ConnectivityActionReceiver( 5626): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): ... skip last_72_check
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 7828): onCreate
,D/BadgeProvider( 7828): DatabaseHelper
,E/Zygote  ( 7862): MountEmulatedStorage()
E/Zygote  ( 7862): v2
I/libpersona( 7862): KNOX_SDCARD checking this for 10178
I/libpersona( 7862): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7862 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7862): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 7828): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/libprocessgroup(  889): failed to open /acct/uid_10033/pid_6946/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7862): TimaSignature is unavailable
,D/ActivityThread( 7862): Added TimaKeyStore provider
,D/BadgeProvider( 7828): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7828): sendNotify, [notify] : null
D/BadgeProvider( 7828): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7828): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7828): update, [UpdateCount] : 1
,D/Launcher.Model( 1488): reloadBadges entered.
,W/ActivityManager(  889): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 7862): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  889): Killing 6922:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2408): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup(  889): failed to open /acct/uid_10099/pid_6922/cgroup.procs: No such file or directory
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2408): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7147): notifyNetworkActivated
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,W/ContextImpl( 7147): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,W/ActivityManager(  889): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 2408): [AccountUtils] Account not ready
W/Kids    ( 2408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2408): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2408): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2408): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2408): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2408): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2408): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2408): 	at java.lang.Thread.run(Thread.java:818)
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/hcjo    ( 7147): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7147): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7147): exit::IDLE
D/InitializeManagerStateMachine( 7147): entry::NETWORK_CHECK
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/Hs20UtilService( 1301): Starting #8
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Hs20UtilService( 1301): Message received 5007
,D/InitializeManagerStateMachine( 7147): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 7147): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7147): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7147): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7147): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7147): entry::SUCCESS
D/hcjo    ( 7147): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7147): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7147): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7147): exit::SUCCESS
D/InitializeManagerStateMachine( 7147): entry::IDLE
,I/Hs20UtilService( 1301): Starting #9
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1301): Starting #10
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  889): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/Hs20UtilService( 1301): Starting #11
,I/Hs20UtilService( 1301): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  889): MasterInitialState.processMessage what=3
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  889): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  889): SmartBondingReceiver: wifi ap is not changed
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  889): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
,D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  889): CLocinfo wifi true 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  889): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1920): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3810): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3810): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 2212): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,I/NetworkMonitor( 5374): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 2212): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SystemBroadcastReceiver( 7169): [#DCM#] [DCM_Performance] onReceive completed in time  223 microsec. 
,I/SystemBroadcastReceiver( 7169): [#DCM#] Calling notifyListeners. 
I/DCMController( 7169): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7169): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WifiStateMachine(  889): callSECApi what=220
,D/WifiStateMachine(  889): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7169): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7169): [#DCM#] onCreate FrameworkService 
,I/FrameworkService( 7169): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7169): [#DCM#] getSuccessState = true
I/FrameworkService( 7169): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
,I/IntentHandler( 7169): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,I/PCWCLIENTTRACE_PushUtil( 6784): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6784): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6784): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  249): id=17 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,I/SystemUtils( 7169): [#DCM#] LM: false,AM:699199488
,D/PowerManagerService(  889): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=889
,D/DisplayPowerController(  889): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PowerManagerService(  889): [s] DisplayPowerCallbacks : onStateChanged()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DCMThreadPoolExecutor( 7169): [#DCM#] Task being added DatabaseRebuilderTask
I/DCMThreadPoolExecutor( 7169): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2acc6bc9 is submitted
I/FrameworkService( 7169): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 28564 mirosec. 
,D/lights  (  889): lcd : 8 +
D/DisplayPowerController(  889): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DatabaseRebuilderTask( 7169): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7169): [#DCM#] resyncLocation   
,I/DatabaseRebuilderTask( 7169): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DIAGMON_AGENT( 7572): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7572): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/lights  (  889): lcd : 8 -
,D/DisplayPowerController(  889): getFinalBrightness : 8 -> 8
,I/DatabaseRebuilderTask( 7169): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7169): [#DCM#] No of Location data to be added:  0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DatabaseRebuilderTask( 7169): [#DCM#] releaseLuceneReader done 
,I/DatabaseRebuilderTask( 7169): [#DCM#] Starting media manager do operation 
I/SystemUtils( 7169): [#DCM#] setHeavySharedPref set as  false
,I/IntentHandler( 7169): [#DCM#] Stopping service with ids up to  1
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/DCMThreadPoolExecutor( 7169): [#DCM#] afterExecute FutureTask
I/DCMController( 7169): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@2acc6bc9
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/FOTA_Client( 7588): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7588): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7588): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7588): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7588): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7605): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7605): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449756662773
,I/KLMS-2.4.503: ( 7605): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/KLMS-2.4.503: ( 7605): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7605): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7605): NetworkChangeOperations(): uploadRequestLog().START 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/KLMS-2.4.503: ( 7605): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/SO_AGENT( 7620): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/SPPClientService( 5268): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6825): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6825): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6825): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6825): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6825): [SCU] == networkStateCheck == true
,I/SA      ( 6825): [DM] getCountryCodeFromCSC : DE
I/SA      ( 6825): isChinaCountryCode : false
I/SA      ( 6825): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6825): [OR] == networkStateCheck true ==
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,I/SA      ( 6825): [OR] GetMyCountryZoneTask
,I/SA      ( 6825): [OR] onReceive END
,I/SA      ( 6825): [SRS] prepareGetMyCountryZone
,I/SA      ( 6825): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6825): [SSP] query invoked
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  889): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  889): [PWL] On : 76863 (30000 ms ago)
,I/PowerManagerService(  889): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService(  889): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=889, ws=WorkSource{10059}) (elapsedTime=289)
,I/SA      ( 6825): [TPMU] GetMccFromDB : null
,D/accuweather( 7644): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7644): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/SA      ( 6825): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6825): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7666): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7666): premStatus:2
,I/KnoxUsageLogPro( 7666): isEulaShown : false
I/KnoxUsageLogPro( 7666): KnoxUsageReceiver onReceive : not Processible, just return
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1169): value : false
,E/File    ( 6825): fail readDirectory() errno=2
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/Headlines( 5521): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5521): getCountryCode(): countryCode = DE
,D/Headlines( 5521): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5521): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5521): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5521): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5521): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7758): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/QuickConnect( 7758): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7758): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/RCPManagerService(  889): exchangeData() failure , invalid userId
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7479): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7479): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7479): StateMachine : Current State = 1
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7479): StateMachine : Changed Current State = 1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/com.peel.receiver.ConnectivityActionReceiver( 5626): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): last run: 1449746146708 -- System.currentTimeMillis()-last_run: 10516321
D/com.peel.receiver.ConnectivityActionReceiver( 5626): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 5626): ... skip last_72_check
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2408): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2408): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7147): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7147): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7147): exit::IDLE
D/InitializeManagerStateMachine( 7147): entry::NETWORK_CHECK
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/jxcore-log( 7422): BLE supported!!
I/jxcore-log( 7422): 
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7147): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7147): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7147): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7147): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7147): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7147): entry::SUCCESS
D/hcjo    ( 7147): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/hcjo    ( 7147): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7147): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7147): exit::SUCCESS
D/InitializeManagerStateMachine( 7147): entry::IDLE
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2408): [AccountUtils] Account not ready
W/Kids    ( 2408): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2408): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2408): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2408): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2408): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2408): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2408): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2408): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2408): 	at java.lang.Thread.run(Thread.java:818)
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
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
,E/WifiStateMachine(  889): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  889): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  889): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
E/WifiStateMachine(  889): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  889): identical MTU - not setting
,D/SmartBondingService(  889): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  889): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
D/SmartBondingService(  889): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
D/SmartBondingService(  889): getSBEnabled() enabled =false
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,W/NetworkManagementService(  889): route cmd failed: 
W/NetworkManagementService(  889): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  889): '
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  889): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  889): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  889): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  889): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  889): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  889): calling update connectivity
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  889):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  889): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524295
,I/SA      ( 6825): [RC New] Execute method=[GET] start
,I/SA      ( 6825): [RC New] Security=[true]
,I/System.out( 6825): Thread-1105(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6825): Thread-1105(ApacheHTTPLog):isShipBuild true
,I/System.out( 6825): Thread-1105(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  889): SIOP:: AP = 400, PST = 429, CUR = 300
,D/X       (  889): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7169): [#DCM#] [DCM_Performance] onReceive completed in time  984 microsec. 
,D/ContentApp( 1222):  LEVEL : 0
,E/TranscodeReceiver( 7227): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 7227):  SIOP_LEVEL: 0
,I/SystemBroadcastReceiver( 7169): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7169): [#DCM#] onReceive action = EVENT_SIOP
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/dhcpcd  ( 7635): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6825): [RC New] [v2liruge] api execute + 623
,I/SA      ( 6825): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6825): AsyncTask #1 calls detatch()
,I/SA      ( 6825): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6825): [OCP] update openData : PL
,I/SA      ( 6825): [TPMU] getNetworkMcc : 
,I/SA      ( 6825): [SCU] saveMccToPreferece Start
,I/SA      ( 6825): [SCU] RegionMCC : 260
I/SA      ( 6825): [SSP] query invoked
,I/SA      ( 6825): [TPMU] GetMccFromDB : null
,I/SA      ( 6825): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6825): [SCU] saveMccToPreferece End
,I/SA      ( 6825): [RC New] executeRequest [v2liruge] end. 711
,I/SA      ( 6825): [RC New] Execute end
I/SA      ( 6825): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6825): [OR] GetMyCountryZoneTask Success
,I/WifiStateMachine(  889): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  889): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GAV4    ( 7700): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1642): Connected
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1642): Message class com.google.f.a.a.p
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCM     ( 2408): Message from null null
,E/GCM     ( 2408): Dropping message from null
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PowerManagerService(  889): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 889) eventTime = 110058
,D/PowerManagerService(  889): [s] UserActivityState : 4 -> 1,
D/PowerManagerService(  889): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=889 (0x0)
D/PowerManagerService(  889): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=889, ws=WorkSource{10059}) (elapsedTime=3486)
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
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6784): mConnectivityHandler : connected
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6784): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6784): ================================================
I/CSTORAGE( 6784):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6784): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6784): [GetString-S]
E/art     ( 6784): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6784): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6784): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6784): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6784): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6784): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6784): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 7635): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/dhcpcd  ( 7635): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7635): wlan0: no IPv6 Routers available
,D/FactoryTest( 6506): Not factory mode
,D/FactoryTest( 6506): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6506): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6506): still no open session command from host, so toast
,W/ContextImpl( 6506): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6506): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6506): Timeline: Activity_launch_request id:com.android.settings time:116278
,E/PersonaManagerService(  889): inState():  stateMachine is null !!
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  889): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  889): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  889): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/MTPRx   ( 6506): started activity for popup
,I/SQLiteSecureOpenHelper( 3541): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3541): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/ResourcesManager( 6506): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6506): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6506): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6506): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6506): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6506): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6506): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6506): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/PreloadUpdateManagerStateMachine( 7147): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7147): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7147): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7147): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,E/SettingsReceiverActivity( 6506): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,E/ActivityManager(  889): Invalid thumbnail dimensions: 576x576
,D/InputMethodManagerService(  889): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  889): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1b1b8915 attribute=null, token = android.os.BinderProxy@21e87626
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/hcjo    ( 7147): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7147): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7147): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7147): entry::IDLE
,I/SQLiteSecureOpenHelper( 3541): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3541): getDatabaseLocked(b,b,pwd)...
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6506): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6506): dev.kiessupport is : TRUE
,D/Activity( 6506): performCreate Call secproduct feature valuefalse
D/Activity( 6506): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/ActivityManager(  889): post active user change for 0
D/KnoxTimeoutHandler(  889): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  889): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/Timeline( 7422): Timeline: Activity_idle id: android.os.BinderProxy@1c985ea0 time:116544
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/PreloadUpdateManagerStateMachine( 7147): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7147): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7147): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7147): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7147): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7147): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7147): entry::IDLE
,D/SSRM:m  (  889): SIOP:: AP = 370, PST = 419, CUR = 300
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,V/AlarmManager(  889): waitForAlarm result :4
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6672): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6672): [1] 5.onFinished: Scheduling replication attempt 3.
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,D/CustomFrequencyManagerService(  889): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  889): mDVFSHelper.release()
,D/CustomFrequencyManagerService(  889): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/CustomFrequencyManagerService(  889): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 889  tag : ACTIVITY_RESUME_BOOSTER@10
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!,
I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,I/ActivityManager(  889): Waited long enough for: ServiceRecord{30c39770 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 340, PST = 404, CUR = 300
D/X       (  889): broadcastSiopLevelIntent:: currentSiopLevel = -1
,I/SystemBroadcastReceiver( 7169): [#DCM#] [DCM_Performance] onReceive completed in time  651 microsec. 
,D/ContentApp( 1222):  LEVEL : -1
,I/SystemBroadcastReceiver( 7169): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7169): [#DCM#] onReceive action = EVENT_SIOP
,E/TranscodeReceiver( 7227): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7227):  SIOP_LEVEL: -1
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/Watchdog(  889): !@Sync 4
,E/SMD     (  288): DCD ON
,D/PowerManagerService(  889): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  889): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  889): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  889): getFinalBrightness : 1 -> 1
,D/lights  (  889): lcd : 1 +
,D/lights  (  889): lcd : 1 -
,D/DisplayPowerController(  889): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 330, PST = 388, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  889): waitForAlarm result :4
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6672): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6672): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): applyOpen
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  889): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  889): CMD_RSSI_POLL : out!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/PowerManagerService(  889): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  889): Nap time (uid 1000)...
,I/PowerManagerService(  889): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  889): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  889): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI(  889): setDeviceInteractive: 0
,D/PowerManagerService(  889): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  889): handleSandman : startDream()
,D/InputManager-JNI(  889): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  889): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  889): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  889): Sleeping (uid 1000)...
,D/InputManager-JNI(  889): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  889): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  889): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  889): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  889): sysfs_write -: /sys/class/input/event1/device/enabled: 0
I/SurfaceFlinger(  249): id=18 createSurf (1080x1920),2 flag=404, ColorFade
,D/SContextService(  889): 	.unregisterCallback : 1, client=
,D/SContextService(  889): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3158e441, Service = Auto Rotation, used = 1
,W/CAE     (  889): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  889): stop(ContextProvider.java:149)
,V/CAE     (  889): clear(AutoRotationRunner.java:182)
,V/CAE     (  889): disable(AutoRotationRunner.java:171)
,I/CAE     (  889): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  889): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  299): sendContextData: -78, 7, 0, 0
,D/CAE     (  889): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  889): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  889): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  889): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  889): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  889): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  889): removeSContextService() : service = Auto Rotation
D/SContextService(  889): ===== SContext Service List =====
D/SContextManager(  889):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3c9d55d1, service=Auto Rotation
,D/KeyguardViewMediator( 1169): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1169): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1169): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1169): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3541): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3541): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): timeout : 5000
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/DisplayPowerController(  889): ColorFade: onAnimationStart
D/DisplayPowerController(  889): getFinalBrightness : 8 -> 0
,D/lights  (  889): lcd : 0 +
D/DisplayPowerController(  889): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1169): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1169): handleNotifyScreenOff
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
D/StatusBar.NetworkController( 1169): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): applyOpen
,D/LightsService(  889): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 889) 
D/LightsService(  889): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  889): [SvcLED]  onSensorChanged::light value = 4
,D/lights  (  889): lcd : 0 -
,D/SensorManager(  889): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  889): unregisterListener ::   
D/lights  (  889): led_pattern : 5 +
,D/BatteryService(  889): turn on LED for fully charged
,D/lights  (  889): led_pattern : 5 -
D/LightsService(  889): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  889): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  889): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  889): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  889): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  299): sendContextData: -76, 13, -46, 0
,I/CAE     (  889): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 11, 36,
,D/SensorHubManager(  889): SendSensorHubData: send data = -63, 14, 14, 11, 36
,D/Sensorhubs(  299): sendContextData: -63, 14, 14, 11, 36
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  889):  handler : SCREEN_OFF end 
,D/NotificationService(  889): ACTION_SCREEN_OFF
,D/LightsService(  889): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 889) 
D/LightsService(  889): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/WifiStateMachine(  889): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  889): handleScreenStateChanged Exit: false
D/LightsService(  889): [SvcLED]  onSensorChanged::light value = 4
,E/WifiStateMachine(  889): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  889): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  889): do suspend true
,D/SensorManager(  889): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  889): unregisterListener ::   
,D/LightsService(  889): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  293): adev_set_parameters: enter: screen_state=off
,V/voice   (  293): voice_set_parameters: enter: screen_state=off
V/voice   (  293): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  293): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  293): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  293): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  293): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  889): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  889): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  889): Bridge Server is not available
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1169): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1169): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1169): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  889): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  889): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1459): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1169):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1169): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1169): dismissHelpPopup 
,D/accuweather( 1920): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1920): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 1920): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  889): !@ ColorFade entry
,D/DisplayPowerController(  889): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  889): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  889): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController(  889): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  889): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  889): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  889): unregisterListener ::   
,E/Sensors (  889): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  889): unregisterListener ::   
,D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/DisplayPowerController(  889): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  889): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  889): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  889): Display changed displayId=0
,W/ActivityManager(  889): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  889): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/StatusBar.NetworkController( 1169): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SystemBroadcastReceiver( 7169): [#DCM#] [DCM_Performance] onReceive completed in time  2428 microsec. 
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SSRM:m  (  889): SIOP:: AP = 330, PST = 375, CUR = 300
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PowerManagerService(  889): [PWL] sb release: PowerManagerService.Broadcasts
,I/SystemBroadcastReceiver( 7169): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7169): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7169): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  277): 
,I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090,
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0,
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  889): Excessive delay in setPowerMode(): 260ms
D/MISC PowerHAL(  889): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService(  889): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  889): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  889): Got set_interactive hint
,I/PowerManagerService(  889): [PWL] Off : 0s ago
I/PowerManagerService(  889): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  889): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  889): getFinalBrightness : 0 -> 0
D/PowerManagerService(  889): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  889): [PWL] sb release: PowerManagerService.Display
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardViewMediator( 1169): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/KeyguardViewMediator( 1169): doKeyguard: not showing because lockscreen is off
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 5s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 330, PST = 366, CUR = 300
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
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
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 123840, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  889): Explicit concurrent mark sweep GC freed 73083(4MB) AllocSpace objects, 29(3MB) LOS objects, 29% free, 37MB/53MB, paused 2.142ms total 223.174ms
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 15s ago
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 320, PST = 357, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  889): !@Sync 5
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 320, PST = 348, CUR = 300
,I/PowerManagerService(  889): [PWL] Off : 30s ago
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/VacuumService( 1642): Vacuum at: now=1449756728597 tag=VacuumService
,D/Netstats( 2408): User is not opted-in to Usage & Diagnostics.
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6672): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6672): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 310, PST = 341, CUR = 300
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7341): Starting books sync, d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7341): null auth token
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8387456024160980947&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8387456024160980947&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8387456024160980947&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/BooksSync( 7341): Soft error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8387456024160980947&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7341): Sync error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-8387456024160980947&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7341): Finished books sync
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162797, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  889): mCursor = null
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1642): Explicit concurrent mark sweep GC freed 43828(2MB) AllocSpace objects, 21(1701KB) LOS objects, 39% free, 17MB/29MB, paused 669us total 43.996ms
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
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
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
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
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
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
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 183014, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  889): mCursor = null
,E/SMD     (  288): DCD ON
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  889): SIOP:: AP = 310, PST = 336, CUR = 300
,I/PowerManagerService(  889): [PWL] Off : 50s ago
,E/SMD     (  288): DCD ON
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  889): waitForAlarm result :4
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6672): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6672): [1] 5.onFinished: Giving up after 6 failures.
,E/Watchdog(  889): !@Sync 6
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 310, PST = 327, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 310, PST = 321, CUR = 300
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 75s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 317, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog(  889): !@Sync 7
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  889): waitForAlarm result :8
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 314, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 311, CUR = 300
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7341): Starting books sync, d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7598913779302582871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7598913779302582871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/PowerManagerService(  889): [PWL] Off : 105s ago
,I/PowerManagerService(  889): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  889): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  889): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=889, ws=WorkSource{10082}) (elapsedTime=2856)
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7598913779302582871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7341): Soft error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7598913779302582871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7341): Sync error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=7598913779302582871&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7341): Finished books sync
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 218895, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  889): Explicit concurrent mark sweep GC freed 52570(2MB) AllocSpace objects, 38(1193KB) LOS objects, 29% free, 37MB/53MB, paused 1.766ms total 139.083ms
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  889): mCursor = null
,W/ProcessCpuTracker(  889): Skipping unknown process pid 8131
,W/ProcessCpuTracker(  889): Skipping unknown process pid 8132
,W/ProcessCpuTracker(  889): Skipping unknown process pid 8134
,W/ProcessCpuTracker(  889): Skipping unknown process pid 8135
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 308, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  889): !@Sync 8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 306, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 304, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/HttpOperation( 6641): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
,E/HttpOperation( 6641): java.io.IOException: Cannot obtain authentication token
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
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
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
D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
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
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 247714, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  889): mCursor = null
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 140s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 303, CUR = 300
,E/Watchdog(  889): !@Sync 9
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 302, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 301, CUR = 300
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/TimaService(  889): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  889): TimaServiceHandler.handleMessage what =1
,D/TimaService(  889): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  889): initializing...
,I/TLC_TIMA_PKM_initialize(  889): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  889): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  889): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  889): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  889): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  889): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  889): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  889): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  889): App is not loaded in QSEE
,D/QSEECOMAPI: (  889): Loaded image: APP id = 3
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,I/TZ: qc_tlc_communication(  889): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  889): Trustlet response is completed
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  889): !@Sync 10
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 7422): Connected to the server!
I/jxcore-log( 7422): 
,I/chromium( 7422): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 180s ago
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  288): DCD ON
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7341): Starting books sync, d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8760807678091569105&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  889): waitForAlarm result :4
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 8204): MountEmulatedStorage()
,E/Zygote  ( 8204): v2
,I/libpersona( 8204): KNOX_SDCARD checking this for 10081
,I/libpersona( 8204): KNOX_SDCARD not a persona
,I/ActivityManager(  889): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8204 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8204): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8204): TimaSignature is unavailable
,D/ActivityThread( 8204): Added TimaKeyStore provider
,D/ResourcesManager( 8204): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  288): DCD ON
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8760807678091569105&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8760807678091569105&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7341): Soft error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8760807678091569105&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7341): Sync error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=8760807678091569105&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7341): Finished books sync
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  889): Killing 6985:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 311912, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  889): failed to open /acct/uid_10020/pid_6985/cgroup.procs: No such file or directory
D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  889): !@Sync 11
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6672): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6672): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6672): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6672): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6672): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6672): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6672): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 6672): Ignoring header User-Agent because its value was null.
,I/System.out( 6672): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6672): (HTTPLog)-Static: isShipBuild true
I/System.out( 6672): (HTTPLog)-Thread-1088-318207773: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  288): DCD ON
,D/SmartBondingService(  889): getSBEnabled() enabled =false
,D/SmartBondingService(  889): getSBEnabled() enabled =false
,E/PlayEventLogger( 6672): Status 503 without retry-after header
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  889): [PWL] Off : 225s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  889): !@Sync 12
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 300, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 299, CUR = 300
,E/SMD     (  288): DCD ON
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  288): DCD ON
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1642): Explicit concurrent mark sweep GC freed 38859(2MB) AllocSpace objects, 29(2MB) LOS objects, 39% free, 17MB/29MB, paused 592us total 40.265ms
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
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
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
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
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
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
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 394679, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2855): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     (  889): Explicit concurrent mark sweep GC freed 51700(3MB) AllocSpace objects, 60(1610KB) LOS objects, 29% free, 37MB/53MB, paused 1.353ms total 94.896ms
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850,
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 300, PST = 299, CUR = 300
,E/Watchdog(  889): !@Sync 13
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 298, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService(  889): [PWL] Off : 275s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 296, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  889): !@Sync 14
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 294, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 293, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  889): !@Sync 15
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7341): Starting books sync, d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6090378238949176302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {,
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6090378238949176302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6090378238949176302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  889): [PWL] Off : 330s ago
,I/PowerManagerService(  889): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  889): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  889): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=889, ws=WorkSource{10082}) (elapsedTime=3539)
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/BooksSync( 7341): Soft error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6090378238949176302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7341): Sync error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6090378238949176302&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7341): Finished books sync
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 466975, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  889): mCursor = null
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 292, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 291, CUR = 300
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/bootchecker(  318): bootchecker wake up!!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 291, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  889): !@Sync 16
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 17
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService(  889): [PWL] Off : 390s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  889): !@Sync 18
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,I/Atfwd_Daemon(  322): Stop the daemon....
,E/Watchdog(  889): !@Sync 19
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 455s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/TimaService(  889): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  889): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  889): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 20
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,I/ActivityManager(  889): Killing 6993:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,W/libprocessgroup(  889): failed to open /acct/uid_10003/pid_6993/cgroup.procs: No such file or directory
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD ON
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 636982, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 21
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 525s ago
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 22
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 23
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7341): Starting books sync, d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,E/SMD     (  288): DCD ON
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/art     ( 1169): Explicit concurrent mark sweep GC freed 74148(4MB) AllocSpace objects, 51(4MB) LOS objects, 30% free, 37MB/53MB, paused 828us total 136.549ms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6385928612850314199&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6385928612850314199&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6385928612850314199&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  889): !@Sync 24
,E/SMD     (  288): DCD ON
,E/BooksSync( 7341): Soft error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6385928612850314199&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7341): Sync error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-6385928612850314199&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7341): Finished books sync
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 730471, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  889): Explicit concurrent mark sweep GC freed 60315(4MB) AllocSpace objects, 113(2MB) LOS objects, 29% free, 37MB/53MB, paused 1.577ms total 124.603ms
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  889): [PWL] Off : 600s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 25
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 26
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 680s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 27
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/Watchdog(  889): !@Sync 28
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  889): !@Sync 29
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  288): DCD ON
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 765s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/TimaService(  889): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  889): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  889): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  889): !@Sync 30
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  889): !@Sync 31
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 32
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 855s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 33
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/LightsService(  889): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  889): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  889): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1642): Message class com.google.f.a.a.i
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GoogleURLConnFactory( 1642): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,E/Uploader( 1642): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1642): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1642): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1642): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1642): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1642): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1642): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1642): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1642): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1642): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/LightsService(  889): [SvcLED]  onSensorChanged::light value = 1
E/LightSensor(  889): Light old sensor_state 8704, new sensor_state : 8192 en : 0
D/SensorManager(  889): unregisterListener ::   
D/LightsService(  889): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/System.out( 1642): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1642): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1642): (HTTPLog)-Thread-199-640908685: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1642): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,I/qtaguid ( 1642): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,W/Uploader( 1642): No account for auth token provided
,I/qtaguid ( 1642): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,W/Uploader( 1642): No account for auth token provided
,I/qtaguid ( 1642): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,W/Uploader( 1642): No account for auth token provided
,I/qtaguid ( 1642): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,W/Uploader( 1642): No account for auth token provided
,I/qtaguid ( 1642): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,W/Uploader( 1642): No account for auth token provided
,I/qtaguid ( 1642): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,W/Uploader( 1642):  no longer exists, so no auth token.
,I/qtaguid ( 1642): Tagging socket 59 with tag 120100000000{4609,0} uid -1, pid: 1642, getuid(): 10012
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 34
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 35
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 950s ago
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 36
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1642): Explicit concurrent mark sweep GC freed 52493(3MB) AllocSpace objects, 63(4MB) LOS objects, 40% free, 18MB/30MB, paused 911us total 100.465ms
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
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
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
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
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
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
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
,D/PanelView( 1169): There is/are notification(s) 
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
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1121386, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  889): mCursor = null
,E/SQLiteLog( 1642): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog(  889): !@Sync 37
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  889): !@Sync 38
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  889): !@Sync 39
,V/AlarmManager(  889): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 1050s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/TimaService(  889): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  889): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  889): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  889): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  889): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  889): Updating Usage Statistics in DB @ 1449757767962
,I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
,W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
,W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	,at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  889): ::getAppControlDB: Exception to create DB
,W/System.err(  889): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  889): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  889): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  889): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  889): Done Updating Usage Statistics in DB @ 1449757768179
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): stay LED for fully charged
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  889): !@Sync 40
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 41
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1169): handleTimeUpdate
,D/KeyguardEffectViewController( 1169): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1169): *** don't update sliding image ***
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1169): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7341): Starting books sync, d
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1642): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-560451089841832993&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
,D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Tagging socket 41 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-560451089841832993&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1642): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1642): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1642): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1642): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1642): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1642): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  889): uri = 14 selection = getSealedState
,D/SecContentProvider2(  889): mCursor = null
D/SecContentProvider2(  889): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  889): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  889): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1169): Icon Only
,D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
,D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): There is/are notification(s) 
,W/GLSActivity( 1642): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1642): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1642): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1642): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1642): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7341): Authentication error
E/BooksAccountManager( 7341): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7341): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7341): null auth token
,I/qtaguid ( 7341): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7341, getuid(): 10082
,I/qtaguid ( 7341): Untagging socket 34
,W/ApiaryClient( 7341): Error response from books API: {
W/ApiaryClient( 7341):  "error": {
W/ApiaryClient( 7341):   "errors": [
W/ApiaryClient( 7341):    {
W/ApiaryClient( 7341):     "domain": "global",
W/ApiaryClient( 7341):     "reason": "required",
W/ApiaryClient( 7341):     "message": "Login Required",
W/ApiaryClient( 7341):     "locationType": "header",
W/ApiaryClient( 7341):     "location": "Authorization"
W/ApiaryClient( 7341):    }
W/ApiaryClient( 7341):   ],
W/ApiaryClient( 7341):   "code": 401,
W/ApiaryClient( 7341):   "message": "Login Required"
W/ApiaryClient( 7341):  }
W/ApiaryClient( 7341): }
,W/ApiaryClient( 7341): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-560451089841832993&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7341): Headers suppressed
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7341): Soft error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-560451089841832993&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7341): Sync error
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7341): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-560451089841832993&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7341): Headers suppressed
E/BooksSync( 7341): 
E/BooksSync( 7341): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7341): Finished books sync
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  889): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1253360, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  889): mCursor = null
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 42
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  889): waitForAlarm result :4
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,I/PowerManagerService(  889): [PWL] Off : 1155s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 43
,V/AlarmManager(  889): waitForAlarm result :8
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,E/SMD     (  288): DCD ON
D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 44
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 45
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 46
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  889): [PWL] Off : 1265s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 47
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 48
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 49
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/TimaService(  889): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  889): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  889): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  889): !@Sync 50
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 1380s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 51
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 52
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 53
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 54
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 1500s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 55
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 56
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 285, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 284, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 57
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 283, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 281, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 58
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 280, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 1625s ago
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 280, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 280, CUR = 300
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 59
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 270, PST = 279, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 279, CUR = 300
,E/SMD     (  288): DCD ON
,D/NetworkStatsFactory(  889): UpdateStatsForKnox
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 279, CUR = 300
,E/SMD     (  288): DCD ON
,D/TimaService(  889): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  889): TimaServiceHandler.handleMessage what =1
,D/TimaService(  889): TIMA: checkEvent, operation: 50000 subject: 10000
,E/Watchdog(  889): !@Sync 60
,E/SMD     (  288): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  889): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  889): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 280, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 281, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 290, PST = 282, CUR = 300
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 61
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED,
,I/MotionRecognitionService(  889): Plugged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/BatteryService(  889): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  889): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  889): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  889): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  889):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  889): Plugged
,D/BatteryService(  889): stay LED for fully charged
,I/MotionRecognitionService(  889): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1169):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3257): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3257): Disconnected process message: 10
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 62
,E/SMD     (  288): DCD ON
,D/ConnectivityService(  889): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 282, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 280, PST = 283, CUR = 300
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  889): [PWL] Off : 1755s ago
,E/SMD     (  288): DCD ON
,D/SSRM:m  (  889): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  288): DCD ON
,E/Watchdog(  889): !@Sync 63
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8567): 
D/AndroidRuntime( 8567): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8567): CheckJNI is OFF
D/AndroidRuntime( 8567): setted country_code = Germany
D/AndroidRuntime( 8567): setted countryiso_code = DE
D/AndroidRuntime( 8567): setted sales_code = DBT
D/AndroidRuntime( 8567): readGMSProperty: start
D/AndroidRuntime( 8567): readGMSProperty: already setted!!
D/AndroidRuntime( 8567): readGMSProperty: end
D/AndroidRuntime( 8567): addProductProperty: start
E/AffinityControl( 8567): AffinityControl: registerfunction enter
D/AndroidRuntime( 8567): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  889): START PACKAGE DELETE: observer{705133999}
D/PackageManager(  889): pkg{<packageName>}
D/PackageManager(  889): user{0}
D/PackageManager(  889): caller{2000}
D/PackageManager(  889): flags{3}
D/PersonaManagerService(  889): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  889): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  889): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  889): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  889): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  889): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  889): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  889): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  889): getApplicationUninstallationEnabled
D/ApplicationPolicy(  889): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  889): !@killApplicatoin: 10367, uninstall pkg
I/ActivityManager(  889): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  889): Killing 7422:com.test.thalitest/u0a367 (adj 0): stop com.test.thalitest
I/ActivityManager(  889): Killing 7758:com.samsung.android.sconnect/u0a138 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7700:com.google.android.apps.magazines/u0a128 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7684:com.android.chrome/u0a88 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 6607:com.sec.chaton/u0a86 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7666:com.sec.knox.bridge/1000 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7644:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 6825:com.osp.app.signin/u0a45 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 6802:com.policydm/1000 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7620:com.sec.android.soagent/u0a37 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7605:com.samsung.klmsagent/u0a19 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7588:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7572:com.sec.android.diagmonagent/1000 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7555:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 5374:com.google.android.music:main/u0a126 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 6784:com.sec.pcw.device/1000 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7169:com.samsung.dcm:DCMService/u0a4 (adj 15): empty for 1801s
I/ActivityManager(  889): Killing 7828:com.sec.android.provider.badge/u0a78 (adj 15): empty for 1802s
I/ActivityManager(  889): Killing 4928:com.android.defcontainer/u0a5 (adj 15): empty for 1839s
I/ActivityManager(  889): Killing 4796:com.google.android.gms.wearable/u0a12 (adj 15): empty for 1840s
I/ActivityManager(  889): Killing 6043:com.sec.android.gallery3d/u0a48 (adj 15): empty for 1846s
I/ActivityManager(  889): Killing 7206:com.sec.android.app.music:service/u0a44 (adj 15): empty for 1846s
I/ActivityManager(  889): Killing 6229:com.google.android.gm/u0a114 (adj 15): empty for 1846s
I/ActivityManager(  889): Killing 7123:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): empty for 1846s
I/ActivityManager(  889): Killing 6722:com.google.android.gms:car/u0a12 (adj 15): empty for 1846s
I/ActivityManager(  889): Killing 7108:com.sec.kidsplat.installer/u0a166 (adj 15): empty for 1846s
I/ActivityManager(  889): Killing 7071:com.samsung.helphub/1000 (adj 15): empty for 1847s
I/ActivityManager(  889): Killing 7055:com.samsung.android.magazine.service/u0a118 (adj 15): empty for 1847s
I/ActivityManager(  889): Killing 7036:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): empty for 1847s
I/ActivityManager(  889): Killing 7015:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1847s
I/ActivityManager(  889):   Force finishing activity ActivityRecord{3bddf366 u0 com.test.thalitest/.MainActivity t12}
D/FocusedStackFrame(  889): Set to : 0
I/ProcessStatsService(  889): Prepared write state in 9ms
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
I/SurfaceFlinger(  249): id=16 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ConnectivityService(  889): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/WifiService(  889): Client connection lost with reason: 4
D/SSRM:m  (  889): SIOP:: AP = 280, PST = 282, CUR = 300
I/art     (  889): Background sticky concurrent mark sweep GC freed 95004(9MB) AllocSpace objects, 366(6MB) LOS objects, 17% free, 38MB/46MB, paused 2.415ms total 108.312ms
W/PackageSettings(  889): Skipping PackageSetting{3b102f5 com.example.hello/10374} due to missing metadata
I/ActivityManager(  889): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
D/ResourcesManager(  889): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/SamsungIME( 1838): mOCRHelper is null
I/art     ( 4624): Explicit concurrent mark sweep GC freed 4026(225KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 589us total 37.312ms
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/InputReader(  889): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 2232): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager(  889): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8596 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 8596): MountEmulatedStorage()
E/Zygote  ( 8596): v2
I/libpersona( 8596): KNOX_SDCARD checking this for 10019
I/libpersona( 8596): KNOX_SDCARD not a persona
I/art     ( 1551): Explicit concurrent mark sweep GC freed 36457(2MB) AllocSpace objects, 1(39KB) LOS objects, 39% free, 16MB/27MB, paused 704us total 79.915ms
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/SELinux ( 8596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/SELinux ( 8596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider( 8596): TimaSignature is unavailable
D/ActivityThread( 8596): Added TimaKeyStore provider
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/SurfaceWidgetView( 1488): destroyHardwareResources():285507851
D/ResourcesManager( 8596): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  889): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  889): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/SecContentProvider2(  889): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  889): mCursor = null
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Books/Books.apk
D/Launcher( 1488): onRestart, Launcher: 676811307
D/Launcher( 1488): onStart, Launcher: 676811307
D/Launcher.HomeView( 1488): onStart
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1920): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1920): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/SurfaceFlinger(  249): id=19 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/StatusBarManagerService(  889): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/StatusBarManagerService(  889): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/RegisteredServicesCache( 1459): empty dynamic service
I/ProcessStatsService(  889): Pruning old procstats: /data/system/procstats/state-2015-12-10-00-44-11.bin
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/KLMS-2.4.503: ( 8596): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 8596): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449758465346
I/KLMS-2.4.503: ( 8596): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8596): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/art     (  889): Explicit concurrent mark sweep GC freed 23185(1725KB) AllocSpace objects, 9(258KB) LOS objects, 29% free, 38MB/54MB, paused 4.754ms total 280.720ms
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/PackageManager(  889): delete codoeFile: 
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/PackageManager(  889): result of delete: 1{705133999}
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/AndroidRuntime( 8567): Shutting down VM
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8615): MountEmulatedStorage()
E/Zygote  ( 8615): v2
I/libpersona( 8615): KNOX_SDCARD checking this for 10104
I/libpersona( 8615): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8615 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  889): Killing 7787:com.android.email/u0a163 (adj 15): empty for 1802s
D/InputMethodManagerService(  889): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/talkback/talkback.apk
W/ContextImpl(  889): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  889): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SELinux ( 8615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/InputMethodManagerService(  889): Got RemoteException sending setActive(false) notification to pid 7422 uid 10367
D/RCPManagerService(  889): PackageReceiver onReceive()
I/HarmonyEASService(  889): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  889): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  889): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  889): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  889): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  889): uID is 10367
V/EnterpriseBillingPolicy(  889): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  889): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  889): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  889): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  889): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  889): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  889): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  889): removeObsoleteFile: deleting file=12_task.xml
D/TaskPersister(  889): removeObsoleteFile: deleting file=12_task_thumbnail.png
D/TimaKeyStoreProvider( 8615): TimaSignature is unavailable
D/ActivityThread( 8615): Added TimaKeyStore provider
D/EnterpriseDeviceManagerService(  889): Package has changed for user 0
D/EnterpriseDeviceManagerService(  889): Admin package name: com.google.android.gms
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
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
D/ResourcesManager( 8615): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
I/Timeline(  889): Timeline: Activity_windows_visible id: ActivityRecord{10d65cf1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:1909542
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/LockPatternUtilsCache( 1169): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1169): value : false
D/elm:14451( 8615): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8615): ELMEngine.ELMEngine( context ).
D/elm:14451( 8615): MDMBridge.setEnterpriseBridge()
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/elm:14451( 8615): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14451( 8615): ElmAgentService : onCreate()
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/elm:14451( 8615): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8615): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8615): MDMBridge.getInstance()
D/elm:14451( 8615): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8615): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8633): MountEmulatedStorage()
E/Zygote  ( 8633): v2
I/libpersona( 8633): KNOX_SDCARD checking this for 10017
I/libpersona( 8633): KNOX_SDCARD not a persona
I/ActivityManager(  889): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8633 uid=10017 gids={50017, 9997} abi=armeabi-v7a
D/ResourcesManager(  889): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 8633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/SELinux ( 8633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14451( 8615): ElmAgentService : onDestroy().
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager(  889): Killing 7479:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1802s
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/TimaKeyStoreProvider( 8633): TimaSignature is unavailable
D/ActivityThread( 8633): Added TimaKeyStore provider
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 8633): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8633): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8633): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8633): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  889): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
E/Zygote  ( 8651): MountEmulatedStorage()
E/Zygote  ( 8651): v2
I/libpersona( 8651): KNOX_SDCARD checking this for 1000
I/libpersona( 8651): KNOX_SDCARD not a persona
W/ResourcesManager(  889): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  889): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  889): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager(  889): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8651 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  889): Killing 7862:com.samsung.android.service.travel/u0a178 (adj 15): empty for 1802s
W/Resources(  889): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  889): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/SELinux ( 8651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8651): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
F/libc    (  889): Fatal signal 7 (SIGBUS), code 2, fault addr 0x6ebae849 in tid 1011 (android.bg)
E/audit_log( 2184): File locking failed. error= Bad file number
E/audit_log( 2184): File locking failed. error= Bad file number
E/WifiManager( 5626): Channel connection lost
W/Sensors ( 1169): sensorservice died [0xaf0d00c0]
E/WifiManager( 1169): Channel connection lost
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6962000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
W/Sensors ( 1488): sensorservice died [0xaf065380]
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (4/8)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/7)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/6)
I/ServiceManager(  247): service 'statusbar' died
I/SurfaceFlinger(  249): id=5 Removed DimLayer (0/5)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (2/4)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/4)
I/ServiceManager(  247): service 'clipboard' died
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/4)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/4)
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/4)
I/ServiceManager(  247): service 'netstats' died
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/4)
I/ServiceManager(  247): service 'wifi' died
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (0/3)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/3)
I/SurfaceFlinger(  249): id=19 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (0/2)
I/ServiceManager(  247): service 'netpolicy' died
I/SurfaceFlinger(  249): id=19 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/2)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (0/1)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/1)
I/ServiceManager(  247): service 'devicestoragemonitor' died
I/SurfaceFlinger(  249): id=18 Removed ColorFade (0/0)
I/SurfaceFlinger(  249): id=18 Removed ColorFade (-2/0)
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
F/libc    ( 8651): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759a5bd8 in tid 8651 (.sec.pcw.device)
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'wifip2p' died
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
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'scheduling_policy' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'meminfo' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'procstats' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
W/Sensors ( 1301): sensorservice died [0x9d6212c0]
W/Sensors ( 2269): sensorservice died [0xaf0beb80]
W/AudioFlinger(  293): power manager service died !!!
W/AudioFlinger(  293): power manager service died !!!
F/libc    ( 8651): Unable to open connection to debuggerd: Connection refused
E/WifiManager( 1551): Channel connection lost
E/WifiManager( 1301): Channel connection lost
W/Sensors ( 1453): sensorservice died [0xaf0beb80]
W/Sensors ( 1471): sensorservice died [0xaf07e340]
E/WifiManager( 1471): Channel connection lost
W/Sensors ( 2232): sensorservice died [0xaf0c1e00]
E/audit_log( 2184): File locking failed. error= Bad file number
E/WifiManager( 2232): Channel connection lost
F/libc    ( 4624): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73d8c311 in tid 4670 (AppProvider)
F/libc    ( 4624): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2184): File locking failed. error= Bad file number
I/Zygote  (  315): Process 8651 exited due to signal (7)
I/Zygote  (  315): Process 4624 exited due to signal (7)
E/SMD     (  288): DCD ON
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
I/SurfaceFlinger(  249): Disp[0] Orientation 0=>0
E/qdoverlay(  249): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  249): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  249): hwc_set_primary: display commit fail for 0 dpy!
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
E/installd(  296): eof
E/installd(  296): failed to read size
I/installd(  296): closing connection
I/lowmemorykiller(  246): ActivityManager disconnected
I/lowmemorykiller(  246): Closing Activity Manager data connection

```
